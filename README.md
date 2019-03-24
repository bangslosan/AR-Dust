# ARKit를 이용해 시각화 한 미세 먼지 정보 앱


> 대기 오염 정도 및 날씨 예보를 해주고 현재 미세먼지 및 날씨를 ARKit 로 시각화 하여 보여준다.

날씨 관련 데이터 수집

- 날씨: 기상청(동네 예보 정보)

- 미세먼지: 한국환경공단 (대기오염 및 측정소 정보)

기능

- 지역별 날씨 보여주기 현재 위치 기반으로 사용자가 위치정보를 허용할 시 현재 위치의 날씨를 제일 먼저 보여준다.

- 미세먼지 관련해서 정보를 보여준다. 그 후 미세먼지의 농도( 한국환경공단에서 정해진 표준에 따라 미세먼지의 시각화를  디자인 한 후 보여준다)

- SNOW 처럼 사람의 코쏙으로 먼지가 들어가고 입을 벌리면 입으로 먼지가 들어가게 하는 방법이 있는 지 ARKit 를 확인 해보기

- 날씨와 미세먼지 따른 시각화를 보여준다


우박
눈
비
안개
맑음

한국환경공단에서 정해놓은 미세먼지 표준 에 의한 AR 시각화 서비스를 제공한다.




외부 라이브러리

- Alamofire (API 연동을 위해)
- coreLocation (위치정보)
- ARKit (미세먼지 가시화)


비슷한 앱

- DustSee (android)



## 진행 상황

- 대기 오염 정보 API 구현
- 근접 측정소로 대기 정보 가져오는데 까지 성공

-   PM10(미세먼지) 농도에 ㄸ
  농도범위 좋음(0 ~ 15)
  농도범위 보통(16 ~ 35)
  농도범위 나쁨(36 ~ 75)
  농도범위 매우나쁨(76 ~ )
  
출처: [에어코리아](http://www.airkorea.or.kr/web)







