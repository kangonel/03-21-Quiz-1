lambda 함수를 사용하여 입력된 숫자를 제곱하는 파이썬 코드는 다음과 같다

<실행코드>
square = lambda x : x ** 2
result = square (10)
print("입력하신 수의 제곱 : ", result)

<기본 소스>
# 사용자로부터 숫자를 입력받습니다.
number = float(input("숫자를 입력하세요: "))

# lambda 함수를 사용하여 제곱을 계산하고 결과를 출력합니다.
print("입력한 숫자의 제곱은:", (lambda x: x ** 2)(number))

위 코드에서 lambda 함수 (lambda x: x ** 2)는 입력값 x의 제곱을 계산한다 
사용자로부터 입력받은 숫자를 lambda 함수에 바로 전달하여 제곱을 계산하고, 그 결과를 출력한다
