# 2020-Unity-Project 
### 게임 명 : 구하자 꽥꽥 
물에 빠져 죽기 직전 오리를 구하는 게임

### 팀원
+ 빅데이터 - 김유진 
+ 콘텐츠 IT - 조윤선

# 1.  프로젝트 개요 
### 구현된 기술 
+ RigidBody -> 총알과 대포총알의 중력
+ Collider -> 총알에 맞았는지 안맞았는지 충돌 체크  is trigger사용
+ canvas - UI -> 게임오버, 누적점수, 시간등 구현
+ GameManger scipt사용 
+ 상속
+ spPoint -> 총알이 나갈 위치 구현
+ deltatime - > 누적시간 계산할때 사용
+ 각종 위치 조정이나 위치값을 받아 올때 Vector3 사용
+ void OnTriggerEnter(Collider coll),tag -> 충돌 체크시 사용

### 개발 환경
+ Unity
+ C# 
+ Team Viewer

# 2. 실행 화면
### 첫 화면
![첫 실행화면](https://user-images.githubusercontent.com/52689951/203958792-aaabac6c-8006-415f-a20a-dd3d6de2b510.png)

### 스토리 
![스토리](https://user-images.githubusercontent.com/52689951/203958852-bf4b17e4-02be-4568-a6a8-7fdbd3ef06c1.png)

### 게임 설명 
![게임 설명](https://user-images.githubusercontent.com/52689951/203958947-28ffe60c-c884-46c7-b0ae-5456e7876e60.png)

### 실행 화면 
![게임 실행](https://user-images.githubusercontent.com/52689951/203959075-a01ad242-ea08-4f06-89d9-98fe71aa7d0d.png)

### 게임 오버
![게임 오버](https://user-images.githubusercontent.com/52689951/203959153-39a32031-2007-4253-a967-a17b44560945.png)

# 개선점 
+ 랜덤 시간으로 총알이 나올 때마다 대포가 다양한 각도(일정 범위 안에서)로 움직이는 것을 어려워서 구현하지 못해 좌우로만 움직이게 만든 점과 총이 회전하는 것에 어느 정도 제한을 두지 못한 점이 가장 아쉽습니다.
# 느낀점
+ 이 게임을 제작하게 되면서 어떤 것을 움직이거나 회전시킬 때 오른쪽 왼쪽이 아닌 3차원 좌표로 생각하는 것이 많이 친숙해졌습니다.  
+ 처음에는 게임을 어떻게 만들까 막막하기만 했는데, 친구와 같이 노력하면서 만들어 완성본을 제출하니 굉장히 뿌듯했습니다.  
+ 수업 시간에 배웠던 내용을 응용해서 만드니 복습하는 기분도 들었고, 그 이후에는 낯설기만 했던 코드들이 어느 정도 눈에 익는 것 같았습니다.
