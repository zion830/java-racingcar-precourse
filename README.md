# [자동차 경주 게임] 구현할 기능 목록

### 1. 사용자의 정보 입력
- 경주할 자동차 이름을 입력받는다.
    - `,`를 기준으로 문자열을 분리해 게임에 참여한 자동차 entry를 생성한다.
    - 유효성 검사 : 문자열이 `, `로 시작하거나 끝날 경우 → 이름이 null인 참가자를 제거한다.
    - 유효성 검사 : 문자열 중간에서 `, ,`처럼 콤마가 연속될 경우 → 이름이 null인 참가자를 제거한다.
    
    
- 시도할 횟수를 입력받는다.
    - 유효성 검사 : 숫자가 아닌 문자가 입력됐을 때, 0 이하의 숫자나 소수가 입력됐을 때 → 재입력을 요구한다.  

### 2. 게임 진행
- 모든 자동차에 대해서
  - 0~9 사이의 랜덤 숫자를 생성
  - 숫자 상태에 따라 자동차의 위치 상태 변경
  
  
- 모든 자동차의 위치 정보 출력

### 3. 게임 종료
- 최종 우승자를 출력한다.
