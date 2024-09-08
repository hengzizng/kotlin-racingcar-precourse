# 자동차 경주 게임

## 기능 목록

- [x] 자동차 이름 입력
  - 자동차는 이름(Name), 위치(Position)를 가진다.
  - 자동차 이름은 쉼표(,)를 기준으로 구분하여 사용자에게 입력받는다.
  - 이름은 5자 이하만 가능하다.

- [ ] 경주 게임
  - 몇 번의 이동을 할 것인지 사용자에게 입력받는다.
  - 주어진 횟수 동안 모든 자동차는 전진 또는 멈출 수 있다.
  - 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다.
  - 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.

- [ ] 자동차 이동
  - 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우 전진하고, 아닐 경우 멈춘다.
  - 모든 자동차들의 이동 후에는 자동차 이름과 위치를 같이 출력한다.

- [ ] 예외처리
  - 사용자가 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시킨다.
  - `IllegalArgumentException` 발생 시 "[ERROR]"로 시작하는 에러 메시지를 출력 후, 그 부분부터 입력을 다시 받는다.
