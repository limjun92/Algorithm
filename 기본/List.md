* 리스트 정렬
```java 

//오름차순
Collections.sort(list);

//내림차순
Collections.sort(list, Collections.reverseOrder());

//대소문자 구분없이 오름차순
Collections.sort(list, String.CASE_INSENSITIVE_ORDER);

//대소문자 구분없이 내림차순
Collections.sort(list, Collections.reverseOrder(String.CASE_INSENSITIVE_ORDER));
```
