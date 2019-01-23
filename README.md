# Drone


# Spec
- ARM Coretex M4

- NUCLEO-F303K8 보드

![img](https://os.mbed.com/media/uploads/bcostm/nucleo_f303k8_2017_10_10.png)


- 핀 정보
 https://os.mbed.com/users/mbed_official/code/mbed-dev/file/default/targets/TARGET_STM/TARGET_STM32F3/TARGET_STM32F303x8/TARGET_NUCLEO_F303K8/PinNames.h/
 
 - 컨트롤러
 https://play.google.com/store/apps/details?id=cc.flexbot.www&hl=ko 
 
 
 # 컴파일 방법
 
 1. https://www.mbed.com/en/ 접속
 2. 회원가입 후 로그인
 3. 홈페이지 상단의 Hardware -> Boards
 4. F303K8 보드 검색후 선택
 5. 우측에 +Add to mBed Compiler 클릭
 6. 홈페이지 상단의 Compiler실행
 7. New -> F303K8 보드 선택 -> 플랫폼:Blinkly test for ST Nucleo boards -> OK 
 8. 코딩~
 
 
 - 이후에는 로그인 후 Compiler 실행
 
 
 # 드론 정보
 
 1. 드론 설정 핀

 D3     D10 /br
    \  /
     ㅁ
    /  \
 D11     D9
 
 D3: 시계방향
 D10: 반시계방향
 D9: 시계방향
 D11: 반시계방향
 
 # 프로토콜
 
 MSP 프로토콜 = MultiWii Serial Protocol
 
 ![img](https://img1.daumcdn.net/thumb/R1920x0/?fname=http%3A%2F%2Fcfile4.uf.tistory.com%2Fimage%2F23494F455910B4CC0EE24C)
