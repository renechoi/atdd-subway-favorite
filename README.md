# 지하철 노선도 미션
[ATDD 강의](https://edu.nextstep.camp/c/R89PYi5H) 실습을 위한 지하철 노선도 애플리케이션

## Step1
### 프로그래밍 요구사항
- 토큰을 이용한 인수 테스트를 작성하기

### 기능 요구사항
- 토큰 생성 API
  - 아이디와 패스워드를 이용하여 토큰을 생성하는 API
  - AuthAcceptanceTest 테스트 성공 시켜야함
  - 인수 테스트 실행 시 미리 데이터가 있어야 하는 경우 데이터를 초기화도 함께 수행하기
- 내 정보 조회 기능
  - 로그인하여 생성한 토큰을 이용하여 내 정보를 조회하는 API
  - MemberAcceptanceTest의 getMyInfo 테스트 완성하기
  - MemberController 의 findMemberOfMine 메서드 구현하기

## Step2
### 프로그래밍 요구사항
- GitHub 로그인을 검증할 수 있는 인수 테스트 구현(실제 GitHub에 요청을 하지 않아도 됨)

### 기능 요구사항
- 깃허브를 이용한 로그인 구현(토큰 발행)
- 가입이 되어있지 않은 경우 회원 가입으로 진행 후 토큰 발행