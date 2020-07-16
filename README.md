# Web-Scrapping-2
기존에 만들어둔 "Web scrapping" 파일과 html을 응용하여 검색엔진을 만들었음.

flask, request, bs4를 이용하였음.

1. Job Search 라는 웹페이지를 만든다.
2. 검색을 통해 Web Scrapping 파일에 저장되어있는 job 데이터를 불러와서 sheet로 표현한다.
3. CSV파일로 다운받을 수 있는 기능을 추가한다.

* 첫 job 검색은 비교적 오래걸릴 수 있음...
* fake db를 이용하여 한번 검색했던 job은 새로 불러오지 않고 바로 보여준다.
* Web Scrapping 파일에 저장되어있지 않은 job을 검색하면 home으로 돌아온다.
* 대문자로 검색했을때 소문자로 변환한다. (ex. REACT -> react)
