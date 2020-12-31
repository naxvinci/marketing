# 발생문제



------

### 1. 직원이 들어간 것인지 판단이 어려움

- 해결법 : Sites & Organizations > Site settings 에 들어가서 직원들의 IP를 block 하기



- **해결!**

### 2. 강의 설명글에서 확대하는지 판단이 어려움

- 참고



### 3. User journey가 끝나지 않았는데 세션이 종료되는 경우

- 참고 - hotjar recordings 중 가장 하단의 18:44 영상 중 5:25~
- **이런 경우 가능한 상황**
- 고객이 30분 동안 한 페이지에서 아무런 동작을 하지 않는 경우 : 세션이 종료되어 다시 돌아오면 새로운 snapshot으로 기록하게 됨
- 다중탭 혹은 다중윈도우창 : 다중탭을 켜놓거나 사이트 내에서 새로운 창이 열리는 경우 트래킹이 어렵다고 함
- Tracking code가 모든 페이지마다 있지 않은 경우 : 코드가 없는 페이지에 들어가면 녹화가 멈춤
- domain이 바뀌는 경우 : 해당 사항 없을 것 같음

### 4. 수강생 구분

- add filter기능
- 혹은 수강생들의 IP를 모두 확인할 수 있으면 1번에서 제시한 해결법으로 해결가능

### 5. iframe 차단 문제

- 영상 강의, 채널톡 등 실행 시



설명 : https://help.hotjar.com/hc/en-us/articles/115011624347-Can-I-Track-iframes-in-Recordings

### 5. heatmaps에서 상단nav바와 겹치는 문제

- 로그아웃 창??이 디폴트로 있어 상단의 메뉴 중 어디를 누른 것인지 판단이 어려움

### 6. heatmaps가 확실히 트래킹을 하고 있는 것인지 판단이 어려움

- 데스트탑과 태블릿에서 아무도 자세히 보기를 누르지 않는

### 7. Snapshots 수 제한 문제

- basic 버전이기 때문에 100개가 찰 때마다 지워줘야 어디서? Once completed, recordings will stop until you start a new snapshot.
- 수강생의 기록은 지워도 될까요? 혹시 필요하지 않을까 해서