## EOF(End Of File)은 데이터 소스로부터 더 이상 읽을 수 있는 데이터가 없음을 의미

* 아래와 같이 사용
```java
BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
String input = "";

while((input = br.readLine()) != null && !input.isEmpty()) {

}
```

* https://gre-eny.tistory.com/307
