# 안내사항
- gitignore 추가해주세요.
- 본인 이름으로 브랜치 만들어주시고 작업한 뒤 그대로 푸시하시고, Pull Request 생성해주세요.
- 본인 이름으로 된 폴더를 생성해주시고, 1번, 2번 프로젝트를 추가해주세요.  

# 1번 : 헬리콥터
![](https://github.com/ChoiSeonMun/Solutions/blob/main/Legacy/03.%20Unity/Helicopter/Helicopter.gif?raw=true)

1. R키를 누르면 시동을 켜거나 끌 수 있다.
    - 시동을 키면 일정 시간동안 프로펠러가 점점 회전하며, 최대 회전 속도에 다다른다.
    - 시동을 끄면 일정 시간동안 프로펠러가 점점 회전을 멈추며 하강하게 된다.
2. 시동을 키고 프로펠러가 최대 회전 속도에 다다른 상태에서 조종을 할 수 있다.
    - W키를 누르면 상승한다.
    - S키를 누르면 하강한다.
    - A키를 누르면 왼쪽으로 회전한다.
    - D키를 누르면 오른쪽으로 회전한다.

# 2번 : 바보포탑
![](https://github.com/ChoiSeonMun/Solutions/blob/main/Legacy/03.%20Unity/Longvinter2/StupidTurret.gif?raw=true)

1. 플레이어는 WASD 키로 이동할 수 있다.
2. 포탑이 플레이어를 감지하면 자동으로 조준하여 총알을 쏜다.
    - 플레이어를 감지하지 않았을 때는 제자리에서 빙글빙글 돈다.
    - 플레이어를 감지했을 때, 플레이어가 조준 가능한 범위를 벗어날 때까지 계속 조준한다.
    - 조준 가능한 범위는 아래와 같다.
![image](https://github.com/Unity-Bootcamp-9/Achievement-Test/assets/17216686/66d17493-1951-473d-b339-c682756a33c4)
    - 총알은 일정 주기마다 발사된다.
3. 총알이 플레이어와 충돌하면 플레이어의 상태는 False가 된다.
