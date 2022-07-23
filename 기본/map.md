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
