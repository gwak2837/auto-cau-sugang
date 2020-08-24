# Auto CAU sugang

중앙대학교 수강신청 오토핫키 매크로

## 권장 환경

AutoHotKey 설치 (필수)

크롬 (권장)

디스플레이 해상도 2560x1440 (권장)

크롬 확대 배율(글꼴 크기) 100% (권장)

크롬 창 최대화 및 북마크바 숨기기 (권장)

- 권장 환경 이외에선 소스 코드 싱 화면 좌표를 직접 수정할 필요가 있다.

## 사용법

1. 자신의 장바구니에 담은 과목 중 잔여여석이 없는 과목의 잔여여석 부분을 캡쳐해서 강의1, 2, 3 등으로 저장한다.

(캡쳐 사진은 컴퓨터마다 다를 수 있으므로 인식의 정확도를 위해 자기 컴퓨터에서 전부 다시 캡쳐하는 것을 권장함)

2. 수강신청 폴더의 Sugang.ahk를 실행한다.

3. F3(완전 자동 모드)을 누른다.

4. 매크로가 잘 실행되고 있는지 지켜본다.

5. 잘 안 되면 F5 기능을 통해 소스 코드의 x, y 좌표를 자신의 컴퓨터 환경에 맞게 적절히 변경한다.

## 기능

### F3

- 평균 4초를 주기로 장바구니 자동 새로고침
- 장바구니에 담은 강의 중 자신이 지정한 강의 3개의 여석을 자동으로 확인
- 해당 강의의 잔여여석이 0이 아니면 수강 신청 시도
- 장바구니 새로고침 횟수, 잔여 여석 확인한 횟수, 수강 신청 시도한 횟수 출력

### F4

- 장바구니 자동 새로고침

### F5

- 마우스 x, y좌표 출력

### F6

- 매크로 일시정지
- 다시 누르면 멈췄던 부분부터 재시작
- 중간에 모드를 변경하려면 프로그램 재시작 필요

### F12

- 매크로 종료
- 오토핫키 프로그램을 완전히(백그라운드까지) 종료하기 위함

## 개발 배경

해마다 이루어지는 수강신청 전쟁과 강의 매매, 언제부터 수강신청이 대학생의 용돈벌이로 전락하게 됐을까요? 이 프로그램은 이러한 현실을 바꾸기 위해 제작됐습니다. 우리와 학생회는 매번 과사나 행장실, 학생 지원처 등에 강의 매매를 줄이기 위해 여석을 늘려주거나, 교수 및 강사를 더 채용하거나, 대형 강의실로 바꾸는 것이 어떠냐고 문의해도 그곳에선 좀처럼 들어주지 않았습니다.

하지만 우리는 이 프로그램을 사용함으로써 강의 매매를 어느 정도 방지할 수 있습니다. 현재 강의 매매는 사람들이 잘 신청하지 않는 시간대를 골라서 이뤄지고 있습니다. 사람은 24시간 수강신청을 하기 어렵다는 점을 이용한 것입니다. 이 프로그램으로 이러한 허점을 보완하면 강의 매매를 줄일 수 있을 것입니다.

- 주의 : 매크로의 수강신청은 사람보다 조금 느립니다. 정시 수강신청 시엔 손으로 하는 것을 권장합니다. 이 프로그램은 단지 여러분의 손은 보다 편안하게 해줄 뿐입니다.
- 주의 : 매크로에 오류가 있을 수 있습니다. 이에 대한 책임은 매크로를 사용한 본인에게 있습니다.

## 법적 쟁점

(2020년 8월 기준) 매크로는 불법이 아닙니다.

(대법원 2017도16520) 정보통신망법 제71조 제9호 및 제48조 제2항의 악성 프로그램은 프로그램 자체를 기준으로 하되, 그 사용 용도 및 기술적 구성, 작동 방식, 정보통신시스템 등에 미치는 영향, 프로그램 설치에 대한 운용자의 동의 여부 등을 종합적으로 고려하여 판단하여야 한다.

https://www.scourt.go.kr/portal/news/NewsViewAction.work?pageIndex=1&searchWord=&searchOption=&seqnum=1768&gubun=6

## 향후 보완점

- 개인 컴퓨터 수강신청 환경에 구애받지 않도록 보완
- 장바구니 내 여러 개의 강의 자동 수강신청
- 장바구니 외 예비과목 및 수강신청 메뉴 과목의 자동 수강신청
