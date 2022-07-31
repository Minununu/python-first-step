# Q. 사이트별로 비밀번호를 만들어 주는 프로그램을 작성하시오

# 예) http://naver.com
# 규칙1 : http:// 부분은 제외 => naver.com
# 규칙2 : 처음 만나는 점(.) 이후 부분은 제외 => naver
# 규칙3 : 남은 글자 중 처음 세자리(nav) + 글자 갯수(5) + 글자 내 'e' 갯수(1)  + "!"로 구성(1)

# 예) 생성된 비밀번호 : nav51!

Url = 'http://naver.com'

replace_Url = Url.replace('http://', '')

slice_Url = replace_Url.find('.')



replace_Url = replace_Url[0 : slice_Url]
# 더 좋은 방법 1. replace_Url = replace_Url[:replace_Url.index(".")]

Password = replace_Url[:3] + str(len(replace_Url)) + str(replace_Url.count('e')) + '!'


print(Password)


