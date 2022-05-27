# Maze
<h2> 콘솔 미로 게임 </h2>

게임 목표: "적을 피해 목적지에 도달하라"

<h3> 구현기능 </h3> <hr>
미로 생성: DFS를 이용해 상하좌우 랜덤으로 길을 뚫어 길이 하나인 완전 미로 생성<br>
적 & 목적지 위치 설정: 플레이어의 위치를 BFS를 활용해 최단 거리를 고려하여 적절한 위치에 적과 목적지를 랜덤으로 생성<br>
적이 플레이어 추적 방법: 적을 기준으로 상 하 좌 우 BFS를 이용해 최단 거리를 구해 가장 짧은 위치로 이동하도록 구현 <br>

<h3> 제작 과정 </h3> <hr>
개발 초기 키보드로 상하좌우 입력받아 플레이어, 적 위치를 이동시키는데 전체를 지우고 콘솔에 다시 그리니 깜빡임이 발생하여<br>
이동 전 위치와 이동 후 위치만 Refresh하여 깜빡임 현상을 수정했습니다. <br>
DFS를 이용해 미로를 만들다 보니 길이 하나만 생성되니 시작부터 승패가 결정나 이런 현상을 개선하고자 랜덤으로 벽을 뚫어 <br>
플레이어의 선택에 더 큰 영향을 받을 수 있도록 수정했습니다.<br>

<h3> 사용기술 </h3> <hr>
C++, BFS, DFS

<h3> 콘솔 화면 </h3>
게임 시작 메인 화면

<img src="https://user-images.githubusercontent.com/69779719/167595972-9a6539b5-2e06-4f68-ad4b-facb7f34c29e.png" width = "400" height = "400">

게임 규칙 화면 

<img src="https://user-images.githubusercontent.com/69779719/167596001-5c023953-063c-4c06-820d-ff861f34529f.png" width = "400" height = "400">

게임 시작 화면

<img src="https://user-images.githubusercontent.com/69779719/167596023-19188e58-d284-4fcc-85b2-b8630a9974c1.png" width = "400" height = "400">

 DFS를 이용해 생성된 미로

<img src="https://user-images.githubusercontent.com/69779719/167596124-f0963479-5ef3-46a1-a4ed-0fc657c6ead9.png" width = "400" height = "400">

<h3> ETC </h3> <hr>
완전 미로 생성 자세히 보기 https://github.com/ckdduf138/Algorithm/tree/main/VC%2B%2B/PerfectMaze
