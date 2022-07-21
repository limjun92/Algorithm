* 빠른 접근
* 중복 허용안함
* 순서 제공안함

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
