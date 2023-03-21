# JPA
JPA Programming

<a href="https://github.com/bboooyaho" target="_blank"><img src="https://img.shields.io/badge/bboooyaho-000000?style=plastic&logo=github&logoColor=FFFFFF"/></a>

<a href="https://www.instagram.com/" target="_blank"><img src="https://img.shields.io/badge/bboooyaho-000000?style=plastic&logo=instagram&logoColor=FFFFFF"/></a>


Inflearn 강좌 - 자바 ORM 표준 JPA 프로그래밍, 김영한 

#객체 지향 프로그래밍이란 추상화, 캡슐화, 정보은닉, 상속, 다형성 등 시스템의 복잡성을 제어할 수 ㅣ있는 다양한 장치들을 제공한다.

#객체(Object)를 영구 보관하는 다양한 저장소는? 
-> RDB, NoSQL, File, OODB
--> 현실적인 대안은 관계형 데이터베이스 
---> 객체를 관계형 데이터베이스에 저장 시, SQL 작성 필요

#객체와 관계형 데이터베이스의 차이는? 
1. 상속  
자바 컬렉션에 저장한다면? list.add(album);
자바 컬렉션에서 조회한다면? Album album = list.get(albumId);
- 부모 타입으로 조회 후 다형성 활용 Item item = list.get(albumId); 

2. 연관관계 
- 객체는 참조를 사용 : member.getTeam() 
- 테이블은 외래 키를 사용 : JOIN ON M.Team_ID = T.TEAM_ID 

#ex. 객체를 테이블에 맞추어 모델링 
class Member {
  String id; //Member_ID 컬럼 사용 
  Long teamId; //Team_ID FK 컬럼 사용 
  String username; //Username 컬럼 사용 
 }
 
 class Team {
  Long id; //Team_ID PK 사용 
  String name; //Name 컬럼 사용 
 }

#ex.객체다운 모델링 






3. 데이터 타입 

4. 데이터 식별 방법 

