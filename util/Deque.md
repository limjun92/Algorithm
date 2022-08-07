* 양쪽 데이터를 추가 삭제가능한 형태

```java

Deque<Integer> dq = new LinkedList<>();

dq.addfirst(1);
dq.addlast(2);
dq.removefirst();
dq.removelast();

//stack기능
dq.push(1); //addfirst(1)
dq.pop();   //removefirst()

//queue기능
dq.add(1);
dq.poll();
```
