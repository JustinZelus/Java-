### 1.使用System.out.println（）時如果傳入的物件，會呼叫物件的toString()方法得到String實例。

``` java
public class Demo { 
    public static void main(String[] args) { 
        Object obj = new Object() { 
                @Override
                public String toString() {
                    return "匿名類別物件"; 
                } 
            }; 

        System.out.println(obj); 
    } 
}
```
