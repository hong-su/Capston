## 캡스톤 디자인 프로젝트 

  공식 프로젝트 명 : 스마트한 자율주행 서비스    
  팀명 :  알아서 잘하자    
  제품명 : 다 비켜 너 빼고    

  
## What's Problem? 
   
  우리는 모두 많은 일정 사이에서 바쁘게 살아갑니다. 그러한 현대인들에게 교통수단은 필수 불가결한 존재입니다. 이러한 교통수단은 우리의 삶을 편리하게 만들어 주지만, 또한 많은 위험에 우리를 노출시킵니다.    
  교통사고에서 가장 위험한 사고들은 대부분 고속도로에서 일어납니다. 차들이 매우 빠른 상태로 달리기 때문에 사고가 나면 그 규모가 크며, 빠르게 달리던 다른 차들과의 2차, 3차 사고로 인해 그 위험성이 더 커지게 됩니다. 졸음운전이나 난폭운전 등 운전자의 문제들도 있지만, 우리가 어찌할 수 없는 부분도 있습니다. 바로 로드킬입니다.    
  로드킬은 연간 약 2000~3000건 정도가 일어납니다. 이는 동물들에게도 매우 안타까운 일이지만, 또한 2차 피해를 불러올 수 있다는 점에서 매우 위험합니다. 갑작스럽게 등장하는 동물들을 피하려다가 끔찍한 사고를 당하는 경우들이 종종 발생합니다. 한순간에 일어나는 일이기 때문에 충분히 사고를 하고 대처를 할 여유가 없이 그저 본능적으로 핸들을 돌리기 때문에 일어나는 안타까운 일입니다. 큰 사고로 이어질 횟수가 무려 약 2500건 이라는 것은 매우 위험한 수치입니다.    
  하지만 동물들이 도로로 뛰어들지 않게 하기 위한 대처는 생각보다 쉽지 않습니다. 도로 개발 등으로 인해 보금자리와 식량을 잃은 동물들은 도로로 내려오게 되며, 모든 도로에 동물 접근 방지 펜스를 설치하는 것도 어렵습니다. 따라서 이에 대한 예방책이 반드시 필요합니다.    
  <p align="center"><img src="https://github.com/2020Capston6/Capston/blob/master/img/news1.png" width="600" height="400"></p>        
  <p align="center"><img src="https://github.com/2020Capston6/Capston/blob/master/img/news2.png" width="400" height="300"></p>
  * 관련링크

  [경향뉴스](http://www.gnnews.co.kr/news/articleView.html?idxno=334036 , "GNN link")     
  [YTN](https://www.yna.co.kr/view/AKR20180918100200062 , "YTN link")

  
  
## GOAL
  <img src="https://github.com/2020Capston6/Capston/blob/master/img/kill_graph.png" width="300" height="300">    
  이렇게 로드킬을 막고자 저희는 로드킬 방지 알고리즘을 제안합니다.    
  하지만 저희 자동차는 만능이 아님니다. 저희 자동차는 모든 센서를 다 부착해서 정확도를 올릴 수는 없습니다.    
  따라서 저희는 소프트웨어의 힘을 빌려 이를 극복하고자 합니다.       
  객체 인식 인공지능 알고리즘을 도입해 효율적인 도로주행 알고리즘을 제시하고자 하는 바가 저희의 목표입니다.       
  

  
## Detail
  
  대략 7~8개의 빌딩블록으로,  그리고 빌딩블록중에는 클라이언트 사이드가 있고, 서버사이드가 있겠고,
  클라이언트 사이드이네느 뭔지 센서가 있겠고, 인터넷 그리모 들어가겠고,  서버사이드에는 database도 있겠고,
  AI 분석 부분도 있겠고, 분석결과를 소비자에게 전달,연결하는 앱이든 액튜에이터든 그런게 있을 것 같습니다.
  
  각 블록다이어그램에 구체적 명칭을 씁니다.  명칭의 예는, esp32보드,  aws ubuntu, node.js/express, GPS센서, 자이로/가속기센서, ... 등등
  대략 이런 정도 느낌을 주면 됩니다. [->링크보기](https://www.google.com/search?q=%ED%81%B4%EB%9D%BC%EC%9D%B4%EC%96%B8%ED%8A%B8+%EC%84%9C%EB%B2%84+%EC%8B%9C%EC%8A%A4%ED%85%9C+%EA%B5%AC%EC%84%B1%EB%8F%84+%EA%B7%B8%EB%A6%AC%EA%B8%B0&tbm=isch&ved=2ahUKEwjM64WJptjoAhVWyosBHeFSC3QQ2-cCegQIABAA&oq=%ED%81%B4%EB%9D%BC%EC%9D%B4%EC%96%B8%ED%8A%B8+%EC%84%9C%EB%B2%84+%EC%8B%9C%EC%8A%A4%ED%85%9C+%EA%B5%AC%EC%84%B1%EB%8F%84+%EA%B7%B8%EB%A6%AC%EA%B8%B0&gs_lcp=CgNpbWcQA1CgpAFY1tIBYJDUAWgIcAB4BoABcogBuB6SAQUxMC4yOJgBAKABAaoBC2d3cy13aXotaW1n&sclient=img&ei=_HuNXsz9HdaUr7wP4aWtoAc&bih=1098&biw=1214#imgrc=g0kmuPL1x7CRtM)
 
  
## Expected Achievement
  
  최소한의 센서로 부터 얻은 정보를 인공지능 알고리즘과 접목시켜 한정적 자원을 소프트웨어의 힘으로 극복해 보고자 한다.    
  한정적인 하드웨어를 사용하는 소형 디바이스의 자율 주행에 도움을 줄수 있는 솔루션을 제공한다.
  
## Teams
  
  팀구성원 : 송민국 장승민 변홍수    
  <img src="https://github.com/2020Capston6/Capston/blob/master/img/1.jpeg" width="150" height="150">
  <img src="https://github.com/2020Capston6/Capston/blob/master/img/2.jpeg" width="150" height="150">
  <img src="https://github.com/2020Capston6/Capston/blob/master/img/3.jpeg" width="150" height="150">    
  ### 역할
    송민국 : 센서 연동
    장승민 : 서버 구축
    변홍수 : 도로주행 알고리즘 설계


## Environment

  github, slack , visual studio code    
  github 중심의 pull request 방식으로 agile 개발한다
  ### 주 계발 방법으로는 XP(eXtreme Programming)을 이용한다.
+ 짧고 반복적인 개발 주기, 단순한 설계를 지향한다.
+ 릴리즈의 기간을 짧게 반복하면서 요구사항을 충분히 반영한다.
+ 핵심가치 : 의사소통 , 단순성 ,용기 ,존중 ,피드백
  
 
## MileStones 
  * 4월 : 센서 연동 확인 
  * 5월 : 도로주행 인공지능 알고리즘 설계
  * 6월 : UI설계
  
