# 9019 G4 DSLR
##### <p align="right"> 2023.04.14 📆 </p>


### 👩‍🏫 풀이
1. 입력받은 숫자를 큐에 넣고 bfs 탐색으로 진행한다.
2. 큐에 들어간 숫자를 꺼내서 D, S, L, R 연산을 하고 각자 큐에 넣습니다.
3. 큐에 넣은 수는 최소 횟수를 위해 방문 표시를 합니다.

<br>

### ⏱️ 성능
<!-- 테이블 -->
성공 |메모리 | 시간 | 코드길이
---|---|---|---|
1|300492KB|3472ms|1623B

<br>

#### PLUS 🔍
처음에는 문자열로 다루는 코드를 짰는데 자릿수가 다른 경우 처리하기 어려워서 숫자로 바꿨다.
테스트케이스를 먼저 봤으면 시간을 덜 들였을 것 같아서 아쉽다.
1시간 10분 걸렸다.