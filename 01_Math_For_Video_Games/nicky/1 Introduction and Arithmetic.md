# 1. 환영 인사

**5 Keys to success**

- Ask a lot
- Immediately practice every concept
- beauty of math
- challenge each other
- feedback

# 2. 덧셈과 뺄셈

- **개발 과정에서 고려해야 하는 것**
  1. `overflow` : 32bit number이 가질 수 있는 값을 넘지 않도록
  2. `type` : +/-할 때 오른쪽 숫자가 whole number(정수)인지 decimal(십진수)일지 등의 숫자 타입 유의
  3. `+` : 기능이 많기 때문에 가끔 문서를 보거나 기능을 override해야 할 수도 있다. 주의!
- +는 순서가 상관없지만 -는 순서가 의미 있다.

# 3. 어림수

- Rounding/Floor/Ceiling
- `9.99`를 소수점 첫째 자리까지 반올림하면 `10.0`이라고 분명하게 작성하자
- 항상 계산의 마지막에 Round하자!
- Math Library가 있어서 편하게 사용한다.

```
Challenge
6.283
Floor: 6, 6.2, 6.28
Ceiling: 7, 6.3, 6.29
```

# 4. 곱셈과 숫자 블록

- `- * -` => `+`
- 4분면에 블록쌓는것처럼 그림을 그려서도 확인할 수 있다

# 5. 나눗셈 Division

- 나눗셈을 반대로 하면 다른 결과가 나온다, 즉 순서가 중요하다
- With `-`, order matters, affects SIGN
- With `/`, order matters, affects SIZE
- Don't devide by 0
- 어떤 컴퓨터에서는 /가 \*보다 느릴 수 있으므로 속도가 중요하면 고려해야 한다
- -, \* => may run out of range
- - => may run out of precision

# 6. Remainders

- 게임에서 내려지는 결정에 사용할 수 있다
  - ex. 랜덤 숫자를 2로 나누어 나머지가 0인지 1인지에 따라 턴을 준다

# 7. BODMAS

- 컴퓨터에서 입력할때는 컴퓨터 형식에 맞게 작성한다 (나누기 모양은 /, 곱하기는 생략하지 않고 \*)
- 프로그램에 따라 연산 우선순위가 다를 수 있다.
  - B: Brackets first / P: Parentheses(괄호) first
  - O: Order / I: Indices / E: Expoonents
  - D: Division / M: Multiplication
  - M: Multiplication / D: Division
  - A: Addition
  - S: Subtraction
- 대부분의 시스템은 곱셈보다 나눗셈을 먼저 한다 (BODMAS)

```
Quiz 1 complete
```
