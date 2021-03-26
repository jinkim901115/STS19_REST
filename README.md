# 프로젝트명: STS19_REST

# 프로젝트에 사용된 기술소개
* JAVA8
* Spring MVC
* AJAX
* MAVEN
* lombok
* Jackson
* Oracle
* css
* JS
* API

# 프로젝트 셋업에 관한 절차
* 이클립스 웹개발세팅
 >  window-PreFerence 에 들어가서 셋팅

*  Tomcat 설치후 -> 셋업

* 프로젝트 작업순서
 > DAO + Mapper생성 -> @Service 생성 -> RestController 생성 -> DTO 생성 후 API 테스트

1. Ajax 용 DAO + Mapper 생성
- MyBatis 버젼으로 매핑할 객체 DAO Interface 와 매퍼파일을 만든다
- 글 삭제’ 는  복수개의 uid 값을 받는다.
- 글 목록’ 에서의 글 전체 개수 → count(*) 
- 글 목록’ 페이징용 쿼리.  

2. @Service 준비
- 기존의 DAO 객체를 통해 운영했었던 코드를을 MyBatis 버젼으로 변경해야 한다
- DAO 이 메소드에서 response 까지 했던거에 반해서 이제는 @RestController 가 자동으로 resposne 해줄수 있도록 리턴 포맷을 맞추어야 한다.

3. @RestController 작성

4. DTO 수정






