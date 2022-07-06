## BufferedReader

```java
import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.util.StringTokenizer;

// BufferedReader
BufferedReader br = new BufferedReader(new InputStreamReader(System.in)); // 선언
String s = br.readLine();
int i = Integer.parseInt(br.readLine());

// StringTokenizer 
// 공백단위로 하나씩 가져온다
StringTokenizer st = new StringTokenizer(br.readLine());
int N = Integer.parseInt(st.nextToken());
int M = Integer.parseInt(st.nextToken());
```

## BufferedWriter

```java
import java.io.BufferedWriter;
import java.io.OutputStreamWriter;

static BufferedWriter bw = new BufferedWriter(new OutputStreamWriter(System.out));

bw.write("abc"); //\n을 사용해서 한줄씩 계속 추가가 가능
bw.newLine();    //줄바꿈?

bw.flush(); // 남아있는 데이터 모두 출력
bw.close(); // 닫기
```

## 예제 문제

* 각 테스트케이스마다 A+B를 한 줄에 하나씩 순서대로 출력한다.

```java
import java.io.BufferedReader;
import java.io.BufferedWriter;
import java.io.IOException;
import java.io.InputStreamReader;
import java.io.OutputStreamWriter;
import java.util.StringTokenizer;

public class Basic {
	public static void main(String[] args) throws NumberFormatException, IOException {
		BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
		BufferedWriter bw = new BufferedWriter(new OutputStreamWriter(System.out));
		StringTokenizer st;
		
		int T = Integer.parseInt(br.readLine());
		
		for(int i = 0; i < T; i++) {
			st = new StringTokenizer(br.readLine());
			int A = Integer.parseInt(st.nextToken());
			int B = Integer.parseInt(st.nextToken());
			bw.write((A + B) + "\n");
		}
		bw.flush();
		bw.close();
	}
}
```
