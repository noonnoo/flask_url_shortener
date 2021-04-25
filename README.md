# flask_url_shortener
* jekins 배포 실험용 프로젝트
* python/flask로 서버구성, html/css로 웹 뷰 구성
* url shortener 페이지로 긴 url을 넣으면 짧은 url로 반환
* dns연결은 안되어있고, ip주소로 연결됨 
* hashids 라이브러리로 url에 매칭되는 hash 값을 반환하여 사이트에서 제공하는 ip뒤에 hash와 매칭되는 사이트로 리다이렉팅

### 초기 화면  
긴 url 입력하면 짧은 url로 변환해 주는 페이지  
![image](https://user-images.githubusercontent.com/33820372/115992975-5cff0500-a60b-11eb-8de4-32c92318db37.png)

### stat  
어떤 URL이 연결되어 있는지, 사용량이 어떠한지 체크하는 페이지  
![image](https://user-images.githubusercontent.com/33820372/115992995-891a8600-a60b-11eb-83f6-87926ba4fb0a.png)
