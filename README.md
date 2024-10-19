# java-calculator-precourse

---

## 구현할 기능 목록 - 문자열 덧셈 계산기

### 입력 기능

- [x] 구분자와 양수로 구성된 문자열을 입력받는다.
    - 잘못된 값을 입력한 경우 경우 예외를 발생한다.

### 핵심 기능

- [x] 입력된 문자열을 쉼표(,) 또는 콜론(:) 구분자로 분리한다.
- [x] 입력된 문자열 앞부분에 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 분리한다.
    - 커스텀 구분자는 1글자 이상일 수 있다. ex) "//;.\n1;.2;.3" 일때 커스텀 구분자는 ";."
- [x] 분리된 문자열에서 숫자들을 정수로 변환하여 합을 계산한다.
- [x] 숫자만 입력한 경우 해당 숫자를 반환한다.
- [x] 빈 문자열을 입력할 경우 0을 반환한다.
- [x] 사용자가 잘못된 값을 입력한 경우 `IllegalArgumentException` 예외를 발생시킨 후 애플리케이션은 종료된다.

### 출력 기능

- [x] 문자열 입력 안내 메세지를 출력한다.
- [x] 덧셈 결과를 출력한다.

### 예외 상황

- [x] 빈 공백을 입력한 경우
- [x] 양수가 아닌 문자를 입력한 경우
- [x] 구분자와 양수 사이에 공백을 입력한 경우
- [x] 커스텀 구분자의 형식에 맞지 않게 입력한 경우
- [x] 지정한 커스텀 구분자 외에 다른 구분자를 입력한 경우
- [x] 커스텀 구분자를 지정하지 않고 기본 구분자 외에 다른 구분자를 입력한 경우