서문
-------

스칼라(Scala)는 객체지향과 함수 프로그래밍을 하나로 통합한 자바와 비슷한 언어이다.
스칼라는 모든 값이 객체인 순수 객체지향 언어이다. 객체의 형(Type)이나 동작은 
클래스(class)로 정의된다. 클래스는 믹스인(mixin)을 사용해 조합될 수 있다. 스칼라는 
순수 언어는 아니지만 주요 언어인 두 언어-자바와 C#-와 매끄럽게 연동될 수 있게 설계되었다.

스칼라는 모든 함수가 값이라는 점에서 함수형 언어이기도 하다. 내포된 함수나 
고차 함수(high-order function)도 제대로 지원한다. 스칼라는 또한 
다른 많은 함수언어에서 사용되고 있는 대수적 형(algebraic type)을 모델링할 수 있는 
일반적인 패턴 매치도 지원한다.

스칼라는 자바와 매끄럽게 상호 연동되도록 설계되었다(.NET을 지원하는 다른 스칼라 구현도 
있다). 스칼라에서 자바 메소드를 호출할 수 있고, 자바 객체를 만들 수도 있으며,
자바 클래스를 상속하거나, 자바 인터페이스를 구현할 수 있다. 이런 작업을 할 때 
별도의 접합용 코드(glue code)가 필요하지 않다.

스칼라는 2001년부터 EPFL의 프로그램 방법론 실험실에서 개발되었다. 1.0 버전은 2003년 
11월 발표되었다. 이 문서는 2006년에 발표된 스칼라 버전 2를 다루고 있다.
이 문서는 언어 정의와 몇몇 핵심 라이브러리 모듈에 대한 참조문서이다. 이 책은 
스칼라나 그 개념을 가르치기 위한 것이 아니다. 그런 목적이라면 다른 문서들이 있다.
[@scala-overview-tech-report; 
@odersky:scala-experiment; 
@odersky:sca; 
@odersky-et-al:ecoop03; 
@odersky-zenger:fool12]

스칼라는 수많은 사람들이 함께 노력한 산물이다. 1.0 버전의 설계와 개발에는 
Philippe Altherr, Vincent Cremet, Gilles Dubochet, Burak Emir, 
Stéphane Micheloud, Nikolay Mihaylov, Michel Schinz, Erik Stenman, 
Matthias Zenger, 그리고 저자 자신이 참여했다. Iulian Dragos, Gilles Dubochet, 
Philipp Haller, Sean McDirmid, Lex Spoon, Geoffrey Washburn은 스칼라와 
도구의 두번째 버전을 개발할 때 참여했다. Gilad Bracha, Craig Chambers, 
Erik Ernst, Matthias Felleisen, Shriram Krishnamurti, Gary Leavens, 
Sebastian Maneth, Erik Meijer, Klaus Ostermann, Didier Rémy, 
Mads Torgersen, Philip Wadler는 이 문서의 1판에 대해 생생하고 
사려깊은 논의와 비판을 제기함으로써 스칼라가 현재의 모습을 갖추는 데 기여했다. 
스칼라 메일링 리스트의 수많은 조력자들도 언어와 도구를 발전시키는 데 도움이 되는 
유용한 피드백을 제공했다.


