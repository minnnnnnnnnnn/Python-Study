# Python-Study
## part_0. 변수, 자료형, 내장함수

파이썬의 변수 선언은 자료형을 명시하지 않고 선언하며, 해당 변수의 자료형은 실제 저장된 변수에 따라 유동적으로 저장된다.

    a=7
    print(a)
    print(type(a))
7

<class 'int'>

출력을 보면 a가 7로 정상적으로 출력되고 있고 a의 type을 출력하니 정수형으로 잘 저장된걸 볼 수 있다.

    a=4.24e-2
    print(type(a))
    print(a)
<class 'float'>

0.0424

같은 예로 이번에도 a가 실수형으로 잘 저장이 되고, 저장 값도 잘 출력되는 것을 볼 수 있다. 

---
파이썬에서 문자열을 선언할 때는 큰 따옴표(""), 작은 따옴표('') 둘 다 사용이 가능하다. 그리고 파이썬에서는 신기하게 큰 따옴표나 작은 따옴표 3개로도 가능하다. 아래 코드를 보자.

    str1 = 'Life is too short'
    str2 = """I enjoy coding"""
    print(str1, end= "\n")
    print(str2)
Life is too short

I enjoy coding

출력을 보면 str1, str2 두 문자열 모두 잘 출력이 되는걸 볼 수 있다.

