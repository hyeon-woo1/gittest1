Spring
========================

동작구조
---------------

클라이언트(사용자)의 모든 요청은 DisparcherServlet이 받는다

DispatcherServlet은 hanlderMapping 을 통해서 요청에 해당하는 controller를 실행시킨다.

Controller는 적절한 서비스 객체를 호출시킨다

Service는 DB처리를 위해 DAO를 ㅣㅇ용하여 데이터를 요청한다.
DAO는 mybatis를 ㅣㅇ용하는 Mapper를 통해 작업 처리를 한다

