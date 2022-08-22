# 나도코딩 파이썬: 4강 문자열

## 1. 문자열

- 변수를 만들어서 print로 출력한다. `sentence = '나는 소년입니다.' -> print(sentence)`
- 문자는 작은 따옴표든 큰 따옴표든 상관없다.

## 2. 슬라이싱

-  슬라이싱 : 문자열에서 필요한 부분만 짤라서 쓰는 것
```
jumin = "970927-1234567"
print( "성별 : " + jumin[7]) -> 성별 : 1
print(" 연 : " + jumin[0:2]) # [0:2] : 0부터 2 직전까지 -> 연 : 97
print( "월 : " + jumin[2:4]) -> 월 : 09
print("일 : " + jumin[4:6]) -> 일 : 27

print("생년월일 : " + jumin[:6]) # 처음부터 6 직전까지 -> 생년월일 : 970927
print("뒤 7자리 : " + jumin[7:]) # 7부터 끝까지 -> 뒤 7자리 : 1234567
print("뒤 7자리 (뒤서부터) : " + jumin[-7:]) -> 뒤 7자리 (뒤서부터) : 1234567
```

## 3. 문자열 처리함수
`python = "Python is Amazing."`
- .lower() : 소문자로 출력 , `print( python.lower()) -> python is amazing.`