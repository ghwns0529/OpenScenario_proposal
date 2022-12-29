# OpenScenario_proposal

------------
> 개요
OpenScenario를 통해 다양한 동적 객체들을 생성하고, 주행 관련 거동을 해석<br/>
https://www.asam.net/index.php?eID=dumpFile&t=f&f=3460&token=14e7c7fab9c9b75118bb4939c725738fa0521fe9#_architecture
>
>
>
>
>
>

# 구조
  * RoadNetWork (entity의 인스턴스로 구성됨)
    * entity 란 road users 등을 지칭
  * Action triggered by condition
  * RoadNetWork 의 road network logic 서술
  OpenDrive 는 road network 의 정적 요소 서술 ex) road, lanes, signs<br/><br/>
  OpenScenario 는 road network 의 동적 요소 서술 ex) traffic maneuvers, weather conditions<br/><br/>
  OpenScenario V1.0 xml 형식의 시나리오 작성(story 구성)<br/><br/>
  OpenScenario V2.0 python 기반 가독성 향상 <br/>
  



# tool
1. Scenario Editor <br/>
Open Scenario Editor is a simple ASAM OpenSCENARIO (*.xosc) editor based on Environment Simulator Minimalistic (esmini).<br/>
  * open scenario editor
  * https://www.youtube.com/watch?v=7id7vQpcQmg
  * https://github.com/ebadi/OpenScenarioEditor

2. esmini <br/>
esmini is a software tool to play OpenSCENARIO files<br/>
  * OpenScenario 작성한 것을 esmini 로 실행
  * https://esmini.github.io/#_hello_world_programming_tutorial
  * https://github.com/esmini/esmini
  
  
  

  
