# image_Drawer
- 콘솔 기반 그림판 - 이미지 연속 재생 프로그램
- 프로그래밍 설계 (2016-03 ~ 2016-07)
- 컴퓨터 통신     (2018-10 ~ 2018-11)

## 팀 구성
- 프로그래밍 설계

  팀장 : 김민기

  팀원 : 이진형, 장병민, 최소정

- 컴퓨터 통신

  팀장 : 김민기

  팀원 : 김도운

## 개발 환경
- Visual Studio 2010
- C/C++

## 사용 기술
- WinApi MouseEvent
- 이중 연결리스트
- 파일 입출력
- 윈도우 소켓 통신

## 기능 설계
- Mouse Event를 통한 콘솔 화면 마우스 접근
- 그림 입력을 배열에 저장, 배열을 각각의 노드로 연결리스트에 저장
- 연결리스트를 임의의 파일 입출력
- 소켓으로 클라이언트-서버 간 파일 입출력

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/0_draw_diagram.png" />
- 그림판 다이어그램

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/0_download_diagram.png" />
- 소켓 업로드 다이어그램

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/0_download_diagram.png" />
- 소켓 다운로드 다이어그램

## 그림판 - 클라이언트 프로그램

### 메뉴 화면
<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 메뉴 화면

### 그리기 화면
(그리기 화면 및 그리기 화면 설명)
<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 그리기 화면/ 커서 옵션

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 그리기 화면/ 페이지 조작

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 그림 예시

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 부분 복사

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 붙여넣기

### 파일 입출력

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 파일 저장

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 파일 불러오기


### 재생
![play](https://github.com/kyu9341/BalanceGame/blob/master/images/balancegame.png)
- 재생


### 서버 접속
<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 서버 파일 업로드

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 서버 파일 다운로드


## 서버 프로그램

### 서버
<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- 클라이언트 대기

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- Sending

<img src="https://github.com/cherrytomato1/image_Drawer/blob/master/readme/1_main.PNG" />
- receive





