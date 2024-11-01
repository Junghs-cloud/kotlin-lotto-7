# kotlin-lotto-precourse

## 구현할 기능 목록
- [x] 입력 받기
  - [x] 구입 금액 입력
  - [x] 당첨 번호 입력
  - [x] 보너스 번호 입력
  - [x] 예외 상황 발생 시 에러 문구 출력하고 다시 시도
    - [x] 구입 금액이 1000원으로 나누어 떨어지지 않는 경우
    - [x] 구입 금액이 숫자가 아닌 경우
    - [x] 당첨 번호가 숫자가 아닌 경우
    - [x] 입력 받은 당첨 번호가 6개가 아닌 경우
    - [x] 보너스 번호가 숫자가 아닌 경우
    - [x] 보너스 번호가 로또 번호와 중복되는 경우
    - [x] 보너스 번호가 1부터 45 사이의 값이 아닌 경우
- [x] 로또 클래스 구현
  - [x] 중복된 값이 없어야 함
  - [x] 번호는 1부터 45 사이의 값이어야 함
- [x] 결과 출력하기
  - [x] 로또를 발행하고 수량과 번호 출력하기
  - [x] 당첨 내역 출력하기
  - [x] 수익률 출력하기