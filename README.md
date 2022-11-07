# 2단계 연관관 계 매핑
### 요구사항
- 아래 DDL을 보고 엔티티간 연관 관계를 설정한다.
- 객체의 참조와 테이블의 외래 키를 매핑해서 객체에서는 참조를 사용하고 테이블에서는 외래 키를 사용할 수 있도록 한다.
- 연관 관계 설정 후 TEST 작업을 진행한다.
- [DB MAPPING](MAPPING.md)

### 개발 기능
- Answer , Question 연관 관계 매핑
- asnewr , User 연관 관계 매핑
- DeleteHistory , User 연관 관계 매핑
- Question , User 연관 관계 매핑


# 1단계 엔티티 매핑

### 요구 사항
- 아래 DDL을 보고 유추하여 엔티티 클래스와 레포지토리 클래스즐 작성한다.
- 레포지토리 및 엔티티를 활용하여 간단한 CRUD TEST 작업을 진행한다.
- [DB SCHEMA](SCHEMA.md)
## 개발 기능
- answer 매핑 및 crud 테스트
- DeleteHistory 매핑 및 crud 테스트
- Question 매핑 및 crud 테스트
- user 매핑 및 crud 테스트
- create_at, update_at을 위한 BaseTimeEntity 생성 
