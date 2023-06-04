# 스프링 데이터 JPA 학습 

## 도메인 모델
### 엔티티 클래스
<img src = "https://user-images.githubusercontent.com/105557972/243177391-84def019-6328-4131-ae5c-956977acba55.png"></img>
### ERD
<img src = "https://user-images.githubusercontent.com/105557972/243177392-be446e15-adc7-4025-b8b0-ca31105d314c.png"></img>
### 공통 인터페이스 기능
  + 순수 JPA 기반 리포지토리 개발
  + 스프링 데이터 JPA 공통 인터페이스 활용  
### 쿼리 메소드 기능
  + 메소드 이름으로 쿼리 생성
  + NamedQuery
  + @Query - 리파지토리 메소드에 쿼리 정의
  + @Query - 값, DTO 조회하기
  + 파라미터 바인딩
  + 반환 타입
  + 순수 페이징과 정렬
  + 스프링 데이터 JPA 페이징과 정렬
  + 벌크성 수정 쿼리
  + @EntityGraph
  + JPA Hint & Lock
### 확장 기능
  + 사용자 정의 리포지토리 구현
  + Auditing
  + Web 확장 - 도메인 클래스 컨번터
  + Web 확장 - 페이징과 정렬
