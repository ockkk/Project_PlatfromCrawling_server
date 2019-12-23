# Platform Crawling Server
파이썬, 장고를 이용하여 유튜브,트위치,아프리카의 셀럽들의 정보를 크롤링하여 데이터를 가공하여 DB에 저장합니다. 

# back-end 사용 스택
Python, Django, selenium

# Crawler 실행 화면

### crawler 실행
![Crawling](https://media.giphy.com/media/JohI8SjDfRtcgsEFEQ/giphy.gif)

### 장고 admin 페이지에서 데이터가 들어갔는지 확인
![Crawling after](https://media.giphy.com/media/RjkpkytBKej9CTiaMB/giphy.gif)

# Crawler Process
![process](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FzMVQi%2Fbtqy32yDblM%2FGJyKMGMzQLOvrOBtp6EYcK%2Fimg.png)

1. 정해진 시간이되면 엑셀에서 BJ 키와 URL이 전장되어 있는 엑셀 파일을 DB에 저장한다. 
2. Platform 테이블의 URL을 읽으면서 크롤링을 시작한다. 
3. 크롤링한 데이터들을 DB에 맞게 가공하여 저장한다. 

# Demon Process
![Demon](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FniL1o%2Fbtqy6UloYpM%2FkOAKDrkJZunkIKvmQgSth1%2Fimg.gif)

1. 스크립트를 나눈다.
2. 스크립트에 실행될 시간을 설정해둔다. 
3. 시간이 되면 해당 시간에 맞춰 스크립트들이 실행된다.
