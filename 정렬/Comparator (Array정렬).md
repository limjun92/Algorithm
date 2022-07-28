```java
Arrays.sort(arr, new Comparator<String>() {
  @Override
  public int compare(String s1, String s2) {
    if(s1.length() == s2.length())
      return s1.compareTo(s2);
    return s1.length() - s2.length();
  }
});
```    


```java
Arrays.sort(arr, (a,b) -> {return (b+a).compareTo(a+b)
