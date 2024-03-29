# - 8차시 Boolean으로 논리 표현하기

### Why?
수에 대한 연산인 산술 연산에는 덧셈(+), 뺄셈(−), 곱셈(×), 나눗셈(÷) 등이 있습니다. 이번 차시에 학습할 조건의 결과(참, 거짓)에 대한 연산입니다. 조건의 결과에 대한 연산인 논리 연산이 바로 불 대수(Boolean algebra)입니다. 불 대수는 AND, OR, NOT과 같은 불 연산자를 사용합니다.

### 학습 목표
- 불 대수의 개념 이해
- 불 연산자의 원리 이해
- 불 대수의 법칙 이해

## 1. 불 대수의 개념
- 불 대수(Boolean algebra)
  - 수 대신 문자를 사용한 논리 연산
- 조지 불(George Boole, 1815~1864)
  - 영국의 수학자, 논리학자

## 2. 불 값
- 참, 거짓
- T(True), F(False)
- 1, 0
- ―○―○―, ―○/○―

## 3. 불 연산자
### 1) AND
- AND, ·, ∧
- 모두 참일 때 참이 됨

|A|B|A·B|
|:---:|:---:|:---:|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

### 2) OR
- OR, +, ∨
- 하나라도 참일 때 참이 됨

|A|B|A+B|
|:---:|:---:|:---:|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|1|

### 3) NOT
- NOT, ￣, ´, ¬, ~
- 반대값이 됨

|A|A´|
|:---:|:---:|
|0|1|
|1|0|

## 4. 불 대수의 법칙
### 1) 교환 법칙
- A + B = B + A
- A · B = B · A

### 2) 결합 법칙
- (A + B) + C = A + (B + C)
- (A · B) · C = A · (B · C)

### 3) 분배 법칙
- A · (B + C) = (A · B) + (A · C)
- A + (B · C) = (A + B) · (A + C)

### 4) 항등 법칙
- A + 0 = A
- A · 1 = A
- A · 0 = 0
- A + 1 = 1

### 5) 보수 법칙
- A + A´ = 1
- A · A´ = 0

### 6) 멱등 법칙
- A + A = A
- A · A = A

### 7) 드모르간의 법칙
- (A + B)´ = A´ · B´
- (A · B)´ = A´ + B´
