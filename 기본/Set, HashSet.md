* 빠른 접근
* 중복 허용안함
* 순서 제공안함

----------

## Collection
* HashSet 중복해서 저장하지 안음
* LinkedhashSet 집합의 특징인 중복을 허용하면서 순서를 가진다.

----------

### method

* size()
* add()


```java
import java.util.Set;
import java.util.HashSet;

public class test{
  public static void main(String args[]){
    set<String> set = new HashSet<String>();
    
    set.add("1");
    set.add("2");
    
    for(Iterator i = set.iterator(); i.hasNext();){
      System.out.println(i.next());
    }
  }
}
```

* set to array

```java
Integer[] arr = set.toArray(new Integer[0]);

Set 객체의 toArray() 메소드를 이용하면, Set 객체를 배열로 변환할 수 있습니다.
파라미터로는, 변환될 배열 객체를 넘겨주면 되는데,
이때 배열의 크기를 0으로 지정하면 자동으로 배열의 크기가 지정됩니다.
```

```
set.contains("1") //true
set.contains("3") //false
```
