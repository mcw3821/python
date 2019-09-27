# python
>>> x=input("첫번째 수:")
첫번째 수:7
>>> y=input("두번째 수:")
두번째 수:3
>>> print("합은",x+y)
합은 73
>>> x=int(input("첫번째 수:"))
첫번째 수:7
>>> y=int(input("두번째 수:"))
두번째 수:3
>>> print("합은",x+y)
합은 10
>>> name=input("당신의 이름은?")
당신의 이름은?채리
>>> print("저는"+name+"입니다.")
저는채리입니다.
>>> max(10,20)
20
>>> min(50,30,20,40)
20
>>> sqrt(4.0)
Traceback (most recent call last):
  File "<pyshell#10>", line 1, in <module>
    sqrt(4.0)
NameError: name 'sqrt' is not defined
>>> from math import*
>>> sqrt(4.0)
2.0
>>> print('BTS가 UN연설에서 말했다.'+'LOVE YOURSELF')
BTS가 UN연설에서 말했다.LOVE YOURSELF
>>> print('BTS 멤버 수는'+str(7))
BTS 멤버 수는7
>>> age=int("100")
>>> height= float("167.51")
>>> age
100
>>> height
167.51
>>> len("student")                  //len = 글자수를 알려줌
7
>>> len("desk")
4
>>>  
>>> print('BTS는 \n사랑이다')
BTS는 
사랑이다
>>> print(r'C:\Cherry\name')
C:\Cherry\name
>>> print("="*30)
==============================
>>> equal="="*30
>>> print(equal)
==============================
>>>
>>> mem=7
>>> print("BTS는 %s명이다."%mem)
BTS는 7명이다.
>>> mem=7
>>> fan=75
>>> print("BTS는 %s명이고 팬은 %s억명이다."%(mem,fan))
BTS는 7명이고 팬은 75억명이다.
>>>  
>>> sentence="BTS는 %s명이고 팬은 %s억명이다."
>>> print(sentence%(7,75))
BTS는 7명이고 팬은 75억명이다.
>>> sent="BTS 좋아"               //sent = 원하는 자리 글자   
          012 3 4 5
>>> sent[2]
'S'
>>> sent[3]
' '
>>> first=input("첫번째 문자열 입력하세요:")
첫번째 문자열 입력하세요:Beyond
>>> second=input("두번째 문자열 입력하세요:")
두번째 문자열 입력하세요:The
>>> third=input("셋번째 문자열 입력하세요:")
셋번째 문자열 입력하세요:Scene
>>> print(first[0]+second[0]+third[0])
BTS
>>> 오늘뭐먹지=['오삼 불고기','쭈꾸미 볶음','폭립','김치찌개','맛 탕']
>>> 오늘뭐먹지
['오삼 불고기', '쭈꾸미 볶음', '폭립', '김치찌개', '맛 탕']
>>> 오늘뭐먹지[0]
'오삼 불고기'
>>> 오늘뭐먹지[3]
'김치찌개'
>>> 오늘뭐먹지[0]='떡볶이'
>>> print(오늘뭐먹지)
['떡볶이', '쭈꾸미 볶음', '폭립', '김치찌개', '맛 탕']
>>> value=90
>>> if(value>=80):
	print("마스크를 쓰세요")
else:
	print("미세먼지가 좋습니다.")

	
마스크를 쓰세요
