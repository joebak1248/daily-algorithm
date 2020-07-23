## 알고리즘 정리
* Stack 사용
    * 배열내부에서 여러개의 시작점,끝 점이 존재할 때 
* Queue 사용
    * 시간 개념이 들어갈 때 (시작시간, 종료시간, 총 걸린 시간 등)
    * LRU 캐시
* DFS 전략
    * 총 경우의 수 구하기
    * 최대 depth 가 정해져 있으면, 최단거리를 구하는데 사용 가능
* BFS 전략
    * 최단거리, 최단 경우의 수 구하기
* DP 전략 < `대회에서 많이 사용된다고 함`
    * n과 관련된 (n-1), (n-2) 가 있을떄, (n-1) + (n-2) = n 으로 표현가능할 때.
* Ad hoc
    * 아이디어로 문제를 해결
    * ex> Sliding Window
    
### 알고리즘 후 겪는 변화들
* 예전보다 코드를 읽는 시간이 많아졌다.
    * before: 문제가 생길때 break point로 따라갔다면
    * after: 코드를 눈으로 보며 문제점들을 파악하는데 더 능숙해졌다.
* `기본기`에 대한 생각의 변화
    * before: 알고리즘과 실무는 별개로 생각 (알고리즘 몰라도 구현은 가능하니까)
    * after: 케이스별로 sort, search 최적화를 `습관적으로` 고민
* 코드 작성의 변화
    * 아무래도 많은 양의 코드를 쓰다보니, stream(), forEach(), map() 과 같이 간결하게 작성하는 잡기술이 생김
