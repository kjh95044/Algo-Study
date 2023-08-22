# 1701 G3 Cubeditor

### 📂 풀이
1. KMP를 이용하여 풀었다.
2. KMP에서 비교하고자 하는 pattern의 접두사와 접미사가 몇 개 일치하는지 구하는 pi배열을 이용하였다.
3. 0번인덱스~끝까지, 1번인덱스~끝까지, ...에 해당하는 부분문자열의 pi배열을 구한다.
4. 그리고 pi배열에서 가장 큰 값이 두 번 이상 나오는 문자열 중 가장 긴 문자열의 길이가 된다.

### 📌 기타
1. KMP가 아직 애매하다.
2. KMP 문제에 조금 더 시간을 할애해야겠다.