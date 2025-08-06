# 문제 제목:

팩토리얼

## 문제 정보

- **출처:** https://www.acmicpc.net/problem/10872
- **난이도:** Medium-- 여기? --Hard

## 문제 설명

0보다 크거나 같은 정수 N이 주어진다. 이때, N!을 출력하는 프로그램을 작성하시오.

## 해결 과정

주어진 정수를 받아 range 함수를 통해 범위를 지정 -> 해당하는 정수를 차례로 곱함

factorial = 1
for i in range(1, n + 1):
factorial \*= i
print(factorial)
이렇게만 했다가 오류
중간에 입력값을 받아야하는데 알아서 미지수에 입력해주는줄 알았네요

### 접근 방법

반복문을 활용하여 주어진 정수를 곱함

## 코드

```python
n = int(input())

factorial = 1
for i in range(1, n + 1):
    factorial *= i
print(factorial)
```
