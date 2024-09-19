<h2><a href="https://www.acmicpc.net/problem/1931">🚀1931번 문제</a></h2>

![image](https://github.com/user-attachments/assets/5cc8f3df-d4fc-4dea-a7f2-27ecdc67a4bb)

<h2>🛠️로직설명</h2>
한 회의실에 배정할 수 있는 최대의 회의 개수를 구하는 문제이다.<br><br>
가능한 많은 회의를 넣으려면 최대한 작은 크기의 회의를 여러개 넣는것이 선택의 폭이 넓어져 합리적이다.<br>
회의가 끝나는 시간보다 회의가 시작되는 시간이 클 수 없으므로, 끝나는 시간 순으로 정렬 후 시작되는 시간 순으로 정렬하면, 회의 기간이 짧은 동시에 희의 시간이 빠른 목록으로 정렬된다.<br><br>
<pre>
  for i in range(N):
    start, end = map(int, sys.stdin.readline().split())
    time.append([end, start])
</pre>
따라서, 위 코드처럼 끝나는 시간을 첫번째 인덱스에 넣고 시작되는 시간을 두번째 인덱스에 넣고 정렬을 시행한다.<br>
<h2>📝오답노트</h2>
<br><br>
