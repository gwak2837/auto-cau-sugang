# Auto CAU sugang

(수강 신청 사이트 개편으로 deprecated)

중앙대학교 (구) 수강신청 오토핫키 매크로

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

2. 수강신청 폴더의 sugang.ahk를 실행한다.

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
