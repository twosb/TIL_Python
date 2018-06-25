### 오와우! 스크래핑은 재밌어!

***

네이버 영화 페이지를 스크래핑 해보았습니다.

Python으로 작성된 오픈 소스 웹 스크래핑 및 크롤링 시스템 라이브러리인 **Scrapy**를 이용하였으며,

Default에서 변경된 파일은 아래와 같습니다.

<br>

>- items.py (modified)
>- settings.py (modified)
>- *in <u>spiders</u> folder* - nm_spider.py (added)

<br>

사실 `pipelines.py` 파일도 건드려야겠지만, 일단 CMD 창에서 결과를 확인할 수 있을 정도로 만들었습니다.

Web Crawling 수업 시간에 배운 내용을 복습하는 차원에서 다시 만들어 보았습니다.



##### * 실행시키기 위해서는?

1. `naver_movie_scraping` 폴더를 다운로드 후 압축 풀기
2. 터미널 창 실행
3. naver_movie_scraping 경로 접속
4. `scrapy crawl naver_movie` 입력



감사합니다. 땡큐 아리가또 쎼쎼! :)