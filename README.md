# Python---3

print('Hello World')
print("Nice to meet you.")
print('Hello "World"')
print("Hello 'World'")
print('Hello','World')
print('Hello'+'World')
     
Hello World
Nice to meet you.
Hello "World"
Hello 'World'
Hello World
HelloWorld

print("\"string\"")
print('\'string\'')
     
"string"
'string'

s1 = '화면에 직접 출력'
s2 = 'ab\c'
s3 = 'does'
print(s1)
print(s2)
print(s3)
print(s1[0])
print(s2[1])
print(s3[1:3])
print(s3[-1])
print(s3[-2])
     
화면에 직접 출력
ab\c
does
화
b
oe
s
e

a = 2
b = 3.14
c = a+b
d = 1e2
e = 1e-2
print(a)
print(b)
print(c)
print(round(c,2))
print("%.2f" % (c))
print(a+b)
print(a,b,a+b,c)
print(d)
print(e)
     
2
3.14
5.140000000000001
5.14
5.14
5.140000000000001
2 3.14 5.140000000000001 5.140000000000001
100.0
0.01

item1 = '사과'
price1 = 1000
item2 = '바나나'
price2 = 500
print(item1, price1)
print(item2, price2)
     
사과 1000
바나나 500

item1 = '사과'
price1 = 1000
item2 = '바나나'
price2 = 500
print(item1, price1, sep=',',end='/')
print(item2, price2)
     
사과,1000/바나나 500

item1 = '사과'
price1 = 1000
item2 = '바나나'
price2 = 500
str1 = '{0}는 {1}원입니다.'
print(str1.format(item1, price1))
print(str1.format(item2, price2))
     
사과는 1000원입니다.
바나나는 500원입니다.

item1 = '사과'
price1 = 1000
item2 = '바나나'
price2 = 500
str2 = '%s는 %d원입니다.'
print(str2%(item1, price1))
print(str2%(item2, price2))
     
사과는 1000원입니다.
바나나는 500원입니다.
