

SmartShoes
==========

<br>

### 1. 프로젝트 개요

<br>

   * 보행자의 걸음걸이를 교정하기 위해 이를 제작, 양쪽 신발에 아두이노가 하나씩 장착이 되며 신발에 기울기 센서, 깔창에 압력센서가 세 개씩 부착된다.
   아두이노는 압력센서에서 읽어들인 데이터를 안드로이드 스마트폰에 전송하며, 보행자는 어플리케이션을 통해 본인이 걸어다니면서 
   한쪽에만 힘을 지나치게 싣지 않았는지 파악하고 이를 토대로 교정 할 수 있다.
    
<br>

### 2. 제품 사용 예시 

  * 신발 
  <br>
  
  ![1](https://github.com/butcher313/Images/blob/master/KakaoTalk_20200804_100907429_04.jpg)

<br>

  * 어플리케이션
  
    + 로딩 화면
      
      ![1.1](https://github.com/butcher313/Images/blob/master/%EB%A1%9C%EB%94%A9%ED%99%94%EB%A9%B4.jpg)
  
    + 메인 화면
      
      ![2](https://github.com/butcher313/Images/blob/master/KakaoTalk_20200804_100907429.jpg)
      
          압력과 각도를 볼 수 있는 화면이다. 어플리케이션에 접속을 하면 먼저 블루투스 ON 버튼을 눌러
          자신의 신발(아두이노)과 통신을 연결 시켜야 한다. 
          신발과 통신 연결이 된 경우, 특정 시간마다 백그라운드로 압력값과 기울기 값이 누적되고 있으며 
          버튼을 누르면 누적된 값의 평균을 내어 위와같이 화면에 표시를 해준다. 
          
    <br>
    
    + 블루투스 연결 화면 
    
    ![3](https://github.com/butcher313/Images/blob/master/KakaoTalk_20200804_100907429_02.jpg)
    
        메인 화면에서 블루투스 ON 버튼을 눌렀을 시 위와같이 장치 선택 화면이 뜬다. 
        HC-06은 신발에 부착된 아두이노의 블루투스 모듈 명이다.
        
    <br>
    
    + GPS 
    
    ![4](https://github.com/butcher313/Images/blob/master/KakaoTalk_20200804_100907429_01.jpg)
    
        GPS 기능을 통해 본인이 지도상 어디에 있는지 확인 가능하다.
        
    <br>
    
    + 교정 화면
    
    ![5](https://github.com/butcher313/Images/blob/master/%EA%B5%90%EC%A0%95%ED%99%94%EB%A9%B4.jpg)
    
        걸음걸이 교정에 대한 도움 자료를 볼 수 있는 화면이다.
