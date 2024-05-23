## 1단계 요구사항
- [x] repository jpa 사용하도록 변경
  - [x] member 변경
  - [x] theme 변경
  - [x] time 변경
  - [x] reservation 변경

## 2단계 요구사항
- [x] 내 예약 목록 API

## 3단계 요구사항
- [X] 멤버의 예약 관리
  - [X] 예약 생성하기
    - [X] (날짜, 테마, 시간, "예약")의 예약이 있으면 실패
    - [X] (멤버, 날짜, 테마, 시간, "예약대기")의 예약이 있으면 실패
  - [X] 전체 예약(예약 및 예약대기) 조회하기
  - [X] 예약대기 생성하기
    - [X] (날짜, 테마, 시간, "예약")의 예약이 없으면 실패
    - [X] (멤버, 날짜, 테마, 시간, "예약대기")의 예약이 있으면 실패
  - [X] 예약대기 삭제하기

## 4단계 요구사항
- [ ] 어드민의 예약 관리
  - [X] 예약 생성하기
    - [ ] (날짜, 테마, 시간, "예약")의 예약이 있으면 실패
  - [ ] 예약 조회하기
  - [ ] 예약 삭제하기
  - [ ] 예약대기 조회하기
    - [ ] 예약 대기 순서가 첫 번째인 예약 대기 정보들만 가져오기
  - [ ] 예약대기 승인하기
  - [ ] 예약대기 삭제하기