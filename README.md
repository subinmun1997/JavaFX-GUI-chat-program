# JavaFX-GUI-chat-program
JavaFX로 만드는 채팅 프로그램

## Toy Project 
> 참고 사이트 : https://www.programmersought.com/article/4685876345/

## Server / Client
* 기본적으로 서버와 클라이언트를 포함하는 프로그램이 있다면, 서버와 클라이언트는 서로 다른 컴퓨터 환경에서 작동을 한다.    
* 실제로 프로그램을 구현한 이후에는 서버 프로그램은 실제 서버(Server)에서 작동시키고, 클라이언트는 해당 서버에 접속을 하는식으로 개발을 한다.    
* 하나의 서버 프로그램은 여러 개의 서버를 구동시킬 수 있다.    
* 하나의 서버 단위마다 쓰레드를 이용해서 작동시킬 수 있다. 이때는 연결을 받아야 하는 것이므로 특정한 포트 번호를 설정해주어야 한다.    
* 이후에 특정한 서버로 클라이언트가 접속하면 해당 서버 쓰레드에서 단위 쓰레드를 클라이언트의 갯수만큼 만들어주어     
  클라이언트가 접속할 때마다 쓰레드를 실행하여 작동시킨다. 

![server](https://user-images.githubusercontent.com/52366841/125409576-fcf05180-e3f6-11eb-8f9b-523ed861ee60.PNG)

* 단순하게 쓰레드만 돌리면 프로그램이 위험한 상태에 처할 수 있다. 그래서 일반적으로 쓰레드 풀(Thread Pool)기법을 사용하여 쓰레드를 관리한다.    

## Server GUI 디자인

![chat](https://user-images.githubusercontent.com/52366841/125409933-5a849e00-e3f7-11eb-835e-2d7d53b8441e.PNG)

<br>

## Client GUI 디자인

![c1](https://user-images.githubusercontent.com/52366841/125410141-90c21d80-e3f7-11eb-9af4-af527a2388df.PNG)

<br>

![c2](https://user-images.githubusercontent.com/52366841/125410177-9b7cb280-e3f7-11eb-94ae-11c130f86d49.PNG)

<br>

![c3](https://user-images.githubusercontent.com/52366841/125410194-9e77a300-e3f7-11eb-95e8-5154d663ccd0.PNG)

<br>

![c4](https://user-images.githubusercontent.com/52366841/125410200-a0416680-e3f7-11eb-913c-5181204d6486.PNG)

<br>
