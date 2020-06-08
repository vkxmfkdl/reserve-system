# 프로젝트 소개

1. 프로젝트 명 : 네이버 예약 시스템

2. 팀원: 박경민

3. 프로젝트 소개: Edwidth 부스트코스 [웹 프로그래밍] 과정을 수강하며 제작한 네이버예약 시스템이다.

4. 개발기간: 2020.05 ~

5. Edwidth 부스트코스 [웹 프로그래밍] 링크: https://www.edwith.org/boostcourse-web/joinLectures/12943

6. 시연영상(메인,상세페이지): https://www.youtube.com/watch?v=1A6mW316tBg&feature=youtu.be

7. 소스코드대신 시연영상 대체하는 이유

<img src="https://user-images.githubusercontent.com/37204852/84009806-c6a00180-a9ae-11ea-99da-cde65c1b9829.png"/>

8. 기술스택: Java, Spring, Mysql, iBatis, Javascript

# 프로젝트 기술요구사항

#### -웹프론트엔드 기술요구사항-

1. DOMContentloaded 이후에 모든 자바스크립트 로직이 동작하게 합니다.

2. 상단영역의 애니메이션은 CSS3의 transition과 transform 속성을 활용해서 구현해야 합니다.

3. TABUI로 구성되는 카테고리 아이템이 노출되는 영역의 HTML은 카테고리별로 각각 만들지 않고 하나로 만들어 재사용합니다.

4. 카테고리 탭을 선택할 때마다, Ajax 요청을 해서 데이터를 가져와야 합니다.

5. 탭 메뉴 (전시/뮤지컬/콘서트 등)는 Event delegation으로 구현합니다.

6. Template 코드를 javascript 함수 안에 보관하지 않고, 별도 분리시켜서 사용해야 합니다. (HTML에 script태그 안에 보관한다던가)

7. 함수 하나에 여러 개의 기능을 넣지 않고, 함수를 여러 개로 분리합니다.
 

#### -웹백엔드 기술요구사항-

1. 제공된 SQL을 이용해서 테이블을 생성하고, 샘플데이터를 입력합니다.

2. maven을 이용해서 웹 어플리케이션 프로젝트를 작성합니다.

3. 학습했던 것처럼 controller,service,dao로 레이어드 아키텍쳐를 구성합니다.

4. spring JDBC를 이용하여 주어진 테이블로부터 입력, 수정, 삭제, 조회하는 DAO와 DTO를 작성합니다.

5. 서비스 인터페이스를 작성하고 해당 서비스 인터페이스에 비지니스 메소드를 작성합니다.

6. 서비스 인터페이스를 구현하는 클래스를 작성합니다.

7. 해당 구현 클래스의 메소드에 적절한 트랜잭션에 관련된 애노테이션을 사용합니다.

8. 클라이언트에게 Web API를 제공하기 위해 RestController 를 작성합니다.

# 프로젝트 구현 요구사항 및 구현영상

#### (1) 프로젝트 구현 요구사항:
#### https://docs.google.com/presentation/d/1i2IC1yIH5ACFCvCH4EMVv_3Zw2oltRvHK94amyNEKbs/edit#slide=id.p5

A. 메인페이지

  1-1. 메인페이지- 카테고리
  
  1-2. 메인페이지- 하단영역
  
  1-3. 메인페이지- GNB & 프로모션 영역
  
B. 상세페이지

  2-1. 상세페이지- 상단영역
  
  2-2. 상세페이지- 하단영역- 예매자 한줄평
  
  2-3. 상세페이지- 예매자 한줄평 전체
  
  2-4. 상세페이지- 하단 상세설명
  
C. 예약하기

  3-1. 예약하기- 상품정보
  
  3-2. 예약하기- 티켓
  
  3-3. 예약하기- 예매자 정보
  
D. 한줄 평 등록

# 프로젝트 구현 이미지

<img src="https://user-images.githubusercontent.com/37204852/83990426-90e62300-a984-11ea-94f0-4f593b2fbf17.png"/>

<img src="https://user-images.githubusercontent.com/37204852/83990484-d1de3780-a984-11ea-9f16-4a09e68f3a4d.png"/>

# ER다이어그램

<img src="https://user-images.githubusercontent.com/37204852/83943594-5a02f680-a838-11ea-90ab-d2558d645c7d.png"/>


