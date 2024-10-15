# java-calculator-precourse

# **예상 시나리오**

---

### 정상 처리

1. 쉼표를 구분자로 넣어 덧셈을 수행한다.
2. 콜론을 구분자로 넣어 덧셈을 수행한다.
3. 쉼표와 콜론을 구분자로 넣어 덧셈을 수행한다.
4. 커스텀 구분자를 넣어 덧셈을 수행한다.

### 예외 처리

1. 아무것도 입력하지 않는다.
2. 지정되지 않은 구분자를 입력한다.
3. overflow를 일으키는 값을 입력한다.

# **구현 기능 목록**

---

### 문자열 입력을 받는 기능

- [x]  ”덧셈할 문자열을 입력해 주세요.” 를 출력한다.
- [x]  문자열을 입력받는다.

### 덧셈을 수행하는 기능

- [ ]  덧셈을 수행한다.
    - [x]  커스텀 구분자가 있는지 확인한다. 
    - [x]  커스텀 구분자를 임시 구분자로 추가한다.
    - [ ]  지정되지 않은 구분자(쉼표, 콜론, 커스텀 구분자 외)가 포함되어 있는지 확인한다.
        - [ ]  아닐 경우, 예외 발생
    - [ ]  더한다.

### 더한 값을 출력하는 기능

- [ ]  결과를 출력한다. (”결과 : 값”)

# **고려할 점**

---

1. 커스텀 구분자가 숫자일 수 있는가?
2. 커스텀 구분자가 여러 자일 수 있는가?
3. 아무것도 입력하지 않았을 경우?
    1. 예시에 있는 것처럼 0을 출력한다.
4. 입력받는 수의 범위는? int, long?