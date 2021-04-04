스마트폰게임프로그래밍  텀프로젝트
========================

스마트폰게임프로그래밍 텀프로젝트 기말프로젝트 준비 / 게임공학부 엔턴테인먼트컴퓨팅전공 2017184017 오선재
----------------------------------

### 게임의 소개
* 컨셉   
  * 모바일판 할리갈리     

  * 유명한 보드게임인 '할리갈리'를 모바일 버전으로 구현한것.    


* 게임방법   
  * 규칙은 간단합니다. 뒤집어진 카드에 그려진 과일의 그림들이, 동일 종류 과일들의 개수의 합이 다섯개가 되었을때 먼저 종을 치는(터치)쪽이 점수를 얻어갑니다. 조건을 만족하지 못했을 때, 그러니까 동일 종류의 과일의 합이 다섯개가 되지 않았을때 종을 치면 패널티를 받아 HP가 깎이게 됩니다. 주어진 턴 수를 모두 마쳤을 때 점수가 가장 높은 쪽이 승리합니다.  
  뒤집어진 카드를 터치해 뒤집고, 뒤집어진 카드의 내용에 따라 동일한 과일의 개수의 합이 5개가 된다면 종을 치며, 아니라면 해당 턴을 넘깁니다.



***



### 개발 범위(최소범위)

* 터치로 카드를 뒤집을 수 있도록 함
* 뒤집어진 카드가 일정시간이 지나면 사라지도록
* 터치로 가운데 종을 칠 수 있도록 (+종소리)
* 일정 조건을 충족한 상태에서 종을 터치시 점수가 올라간다.
* 적 AI(컴퓨터. 일정 속도로 카드를 뒤집음. 일정 범위 내에서 랜덤한 속도로 조건 충족시 종을 침. 일정 확률로 조건 미충족 상태에서 종을 침.)
* 일정 조건 충족시 HP감소
* 턴제. 일정 턴수가 지나면 게임이 종료된다.


***




### 개발 범위(추가범위)

* 타이머 기능(일정시간동안 카드를 뒤집어야 함)
* 카드들중 과일카드가 아닌 특수한 카드가 포함. (공격&회복&점수 보너스 카드) 해당 카드 등장시 종을 먼저 누른 쪽이 상대방을 공격 또는 자신을 회복하거나, 보너스 점수를 얻는 것이 가능.
* 점수 기록 및 최고기록 갱신 여부 구현




***


### 개발 일정

* 1주차: 리소스 수집
* 2주차: 리소스 배치, 터치로 카드 뒤집는 기능 구현
* 3주차: 카드의 리젠 및 터치로 종을 울리도록 구현(소리 추가)
* 4주차: 컴퓨터쪽 AI구현
* 5주차: 점수 기능 구현(+카드의 과일 개수 계산 여부 추가)
* 6주차: 턴제 제한 추가
* 7주차: 패널티 및 게임오버 추가
* 8주차: 게임방법 추가. 테스트로 컴퓨터 AI의 속도 범위 수정 (혹은 추가 범위 구현)
* 9주차: 전체 점검 및 버그 체크
