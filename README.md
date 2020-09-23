
# 프로젝트
구글 확장프로그램 앱 MOMENTUM 클론코딩 프로젝트

사용기술 : css / html / vanilla JS

실행 페이지 : (https://leesoonyong.github.io/momentum/)

![자바스크립트 미니프로젝트](https://user-images.githubusercontent.com/44168355/93973718-a0f90580-fdaf-11ea-924e-8855eb45921f.png)





# 주요기능 

![모멘텀 기능](https://user-images.githubusercontent.com/44168355/93849987-287b4180-fce8-11ea-9701-9d92ea93afd1.png)


* 현재온도 및 현재 위치 

  * navigator api를 통하여 현재 사용자의 위치정보를 받아옵니다 그후 함수를 통하여  localStroange에 저장한 후 저장한 정보를
  * openweathermap api에 넣어준 후 현재 온도와 현재 위치를 html코드에 넣어줍니다 

* 현재시간
  
  * date를 통하여 현재 시간을 불러왔으며 삼항 연산자를 통하여 00:00:00으로 나타나게 표시하였습니다

* 사용자 이름
  * 이벤트 리스너를 활용하여 localStorage에 저장 시킨 후 함수를 통하여 불러오도록 하였습니다

* 오늘의 할일
  * 입력한 값을 toDos배열에 json형태로 넣어준 후 locarStrage에 string으로  변환 후 데이터를 넣어줍니다
  * 넣어준 데이터는 forEach문을 통하여 출력합니다 
  * 삭제는 filter를 통하여 구현하였습니다
  
  
  
  # 마무리
  
  localStorage를 알게해주었던 프로젝트였습니다.
  
  자바스크립트 eventLisner 및 함수 작성에 대해서 많이 연습 할 수 있었습니다.
  
  특히 현재 위치를 구현할때 navigator api를 처음 접하면서 굉장히 신선한 느낌을 받았습니다
  
  
  
