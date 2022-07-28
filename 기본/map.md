----------

## Map 
* HashMap : key-value를 사용
* HashTable : HashMap과 동일하지만 Thread-Safe하여 동기화 지원
* LinkedHashMap : 순서를 가진다.


```java

import java.util.HashMap;

public class Map_Test {
	public static void main(String[] args) throws NumberFormatException, IOException {
  
	HashMap<Integer, Integer> map = new HashMap<>();

	map.put(key, value);
	map.get(key);
	
	map.containsKey(key) // true, false
	
	//for문
	for( String key : map.keySet())
	{
		System.out.println(key + " " +  map.get(key));
	}
}

```
