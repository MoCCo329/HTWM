# HTWM(22/10/11~22/12/25)

<br>

## 서비스 소개

> Home Traning With Mirror

- 거울을 활용해 홈트레이닝 하기
- 홈트와 관련된 여러 기능이 있는 스마트 미러와 앱

<br>

## 팀원 소개 및 담당 역할

- 김보경 (팀장) : App FrontEnd, 발표
- 김도현 (팀원) : Device FrontEnd
- 김준수 (팀원) : BackEnd, App FrontEnd
- 유현우 (팀원) : 자세인식 알고리즘
- 윤희욱 (팀원) : Device 센서 제어
- 최희선 (팀원) : BackEnd, 자세인식 알고리즘, UCC 제작

<br>

## 기술스택

APP FE : React Native, Typescript

Device FE : Electron, React, Redux

BE : Spring Boot, MySQL

Infra : Jenkins, AWS EC2, S3, NginX

Device : Raspberry PI, Jetson NANO, 4 vibration sensor, 3 cameras, OpenCV

<br>

## 서비스

### 1. 앱에서 운동 루틴 관리 및 기기에서 실행

- 원하는 운동 루틴을 만들고 기기에서 레퍼런스 영상을 보며 운동 가능하다. 운동 종류별로 자세에 맞게 카운트를 하여 운동기록을 관리한다.



![Screenshot_20221120-204917_Expo_Go](README.assets/Screenshot_20221120-204917_Expo_Go.webp)<img src="README.assets/image-20230504203323976.webp" alt="image-20230504203323976" style="zoom:50%;" />

<img src="README.assets/1683193635067.webp" alt="1683193635067" style="zoom: 67%;" />

### 2. 화상 PT

- 집에서 화상으로 트레이너 혹은 친구와 PT 를 진행할 수 있다.
- 앱에서 친구에게 통화를 걸고 상대방이 받으면 기기간 연결이 시작된다.

<img src="README.assets/image-20230505001356175.webp" alt="image-20230505001356175" style="zoom: 50%;" />

<img src="README.assets/Gif_25518b4c-0332-4231-acb9-e2404e0246e2.webp" alt="Gif_25518b4c-0332-4231-acb9-e2404e0246e2" style="zoom:33%;" />

### 3. 오운완(오늘 운동 완료) 사진촬영

- 매일 내 모습을 기록하기 위한 사진촬영 기능
- 앱에서 사진을 확인하고 관리할 수 있다.

<img src="README.assets/2.webp" alt="2" style="zoom: 67%;" /><img src="README.assets/Screenshot_20221120-205211_Expo_Go.webp" alt="Screenshot_20221120-205211_Expo_Go" style="zoom:67%;" />

### 4. 음성인식 기기제어, 및 진동감지센서

- "안녕 트윗" 키워드를 통해 음성인식을 실행시키고 운동 시작/종료, 사진촬영 시작, 화상통화 종료 등을 제어 가능하다.
- 진동센서가 있어 거울을 세번 노크하여 사진촬영을 바로 할 수 있다.d

<img src="README.assets/5.webp" alt="5" style="zoom:67%;" />

<img src="README.assets/4.webp" alt="4" style="zoom:63%;" />

<br>

## DEATIL

### 1. Planning & Desing

- 기능적 요구 사항 정리

![기능명세_1](README.assets/기능명세_1.webp)

![기능명세_2](README.assets/기능명세_2.webp)

- 와이어 프레임(앱, 디바이스)

![앱](README.assets/앱-16832143089841.webp)

![웹](README.assets/웹.webp)

- DB Schema - ERD

![erd](README.assets/erd.webp)

- API

![image-20230505003804312](README.assets/image-20230505003804312.webp)

![image-20230505003847005](README.assets/image-20230505003847005.webp)

![image-20230505003933645](README.assets/image-20230505003933645.webp)

![image-20230505004425820](README.assets/image-20230505004425820.webp)

- 아키텍처

![스크린샷 2023-05-04 204213](README.assets/스크린샷 2023-05-04 204213.webp)

### 2. ETC

<img src="README.assets/20221114_153809.webp" alt="20221114_153809" style="zoom:50%;" />

<img src="README.assets/20221117_155856.webp" alt="20221117_155856" style="zoom:50%;" />

<img src="README.assets/1678607111597.webp" alt="1678607111597" style="zoom:50%;" />

<img src="README.assets/20221118_110845.webp" alt="20221118_110845" style="zoom:50%;" />

