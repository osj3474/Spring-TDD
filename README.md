<div align=center>
  <h1> TestCode🎯 와 함께 </h1>
  <br /><br />
</div>


1. In memory DB를 써도 괜찮을까?

   : Not recommended. 운영 환경과 일치하지 않음으로 분명 문제점은 존재한다. 

   cf) <a href="https://umbum.dev/1127" target="_blank">통합 Test에 in-memory DB를 쓰는게 더 좋을까?</a>

   : 대안

   - Testcontainers : JUnit 테스트를 지원하는 Java 라이브러리로, 공통 데이터베이스
   - `-DreuseDatabase` 옵션 : DB 매번 재시작하지 않도록 설정 가능
   - flyway : DDL 및 초기 데이터 관리





