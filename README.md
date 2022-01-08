# RaspberryPi_Bus_BusStop_control
raspberry pi project use python

this is my second project for graduate university

# 기능 흐름 설명
  1. linux 운영체제에 sever.py를 구동시킨다. 
  2. linux 와 bus, bus_stop 모두 동일한 AP(wifi)에 접속한다.
  3. 고정 IP 방식으로 동작하기 때문에 각각의 client에 미리 ip주소를 할당한다.
  4. 서버를 구동시키고, 각각의 클라이언트에서 서버에 접속한다.
  5. 버스 정류장에서 각각의 버스에 해당하는 택트 스위치를 누르면 서버로 데이터를 전송한다.
  6. 버스에서 각각의 버스 정류장에 해당하는 택트 스위치를 누르면 서버로 부터 데이터를 요청한다.
  7. 서버는 버스정류장으로 부터 받은 정보를 저장하고 있다가, 버스의 요청이 있으면, 버스에 해당 정보를 전송하고 그 count 를 0으로 초기화 한다.
 
# 관련 논문 작성

[버스 승객 대기 알림 서비스 - 논문.pdf](https://github.com/9junbeum/RaspberryPi_Bus_alert/files/7191510/-.pdf)


# 공모전 참가
2021 임베디드 소프트웨어 공모전
팀 번호 : 1052 
팀 명 : 타요타요

[2021ESWContest_자유공모_1052_타요타요_개발완료보고서.pdf](https://github.com/9junbeum/RaspberryPi_Bus_alert/files/7832738/2021ESWContest_._1052_._.pdf)


# 시연 동영상(Youtube)
https://www.youtube.com/watch?v=Mnl96Z-PX24

# 개선사항 
동작 감지 또는 lcd 표시 할 때 
inturupt 방식으로 입력을 받도록 한다. 
