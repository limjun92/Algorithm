```java
import java.io.BufferedWriter;
import java.io.OutputStreamWriter;

static BufferedWriter bw = new BufferedWriter(new OutputStreamWriter(System.out));
bw.write(Integer.toString(re[i])+" ");
bw.newLine();

bw.flush(); // 남아있는 데이터 모두 출력
bw.close();
```


```java
BufferedReader br = new BufferedReader(new InputStreamReader(System.in)); // 선언
String s = br.readLine();
int i = Integer.parseInt(br.readLine());

// StringTokenizer 
BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
StringTokenizer st = new StringTokenizer(br.readLine());
int N = Integer.parseInt(st.nextToken());
int M = Integer.parseInt(st.nextToken());

// String.split() 함수
String arr[] = s.split(" ");
```
