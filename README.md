# Notty
## 지하철 하차 알림 서비스


[서비스 링크](http://3.37.150.251:8000/)

<img width="200" alt="스크린샷 2023-01-03 오후 7 13 55" src="https://user-images.githubusercontent.com/88936783/210337842-366e716b-10e6-4590-af38-ab9445c8a6f4.png">
<img width="200" alt="스크린샷 2023-01-03 오후 7 14 04" src="https://user-images.githubusercontent.com/88936783/210337857-5907202b-0972-4d3e-9a9d-dbb951506003.png">
<img width="200" alt="스크린샷 2023-01-03 오후 7 14 19" src="https://user-images.githubusercontent.com/88936783/210337876-9edc613b-4eb7-4313-812e-59a9707dbd55.png">

![Group 1](https://user-images.githubusercontent.com/88936783/210338946-51f2080b-66fa-44fb-ba07-5ed6ae28fb13.png)
![hqdefault](https://user-images.githubusercontent.com/88936783/210338947-82a0f2db-5dfe-427b-b168-5f5cf796071d.jpg)

![그림1](https://user-images.githubusercontent.com/88936783/210338995-1e62a597-bf7e-41ca-954e-71c30fac4dfe.jpg)
![그림2](https://user-images.githubusercontent.com/88936783/210338997-db93d0e3-2746-43a9-bb8b-0880b0a4bbba.jpg)


사용 API

지하철경로조회
kakao 로컬
[서울시 지하철역 정보 검색 (역명)](https://data.seoul.go.kr/dataList/OA-121/S/1/datasetView.do)

[서울교통공사 노선별 지하철역 정보](http://data.seoul.go.kr/dataList/OA-15442/S/1/datasetView.do)

[역코드로 지하철역별 열차 시간표 정보 검색](https://data.seoul.go.kr/dataList/OA-101/A/1/datasetView.do)

[서울교통공사 실시간 지하철 위치 정보](https://data.seoul.go.kr/dataList/OA-12601/A/1/datasetView.do)


FirebaseCloudMesseging 으로 알림 구현

AWS EC2, screen 을 이용하여 24시간, 365일 작동됨
