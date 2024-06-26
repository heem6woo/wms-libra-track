# 📦 문헌 털이단의 도서 창고 관리 시스템(WMS)



## ✏️ 프로젝트 소개


1. 이 프로젝트는 출판사와 창고 간의 도서 재고 관리를 효율적으로 처리하기 위한 시스템입니다.

2.  주요 기능은 사용자 관리, 재고 및 입출고 관리, 그리고 창고 및 출판사 관리로 구성되어 있습니다.


## 📌 프로젝트 기획서


![프로젝트 기획서](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%EB%AF%B8%EB%8B%88%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EA%B8%B0%ED%9A%8D%EC%95%881.png)
![프로젝트 기획서](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%EB%AF%B8%EB%8B%88%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EA%B8%B0%ED%9A%8D%EC%95%882.png)
![프로젝트 기획서](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%EB%AF%B8%EB%8B%88%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EA%B8%B0%ED%9A%8D%EC%95%883.png)


## 📌 요구 사항 명세


![요구 사항 명세](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%20%EB%AA%85%EC%84%B8.png)


## 📌 유스케이스 다이어그램


![유스케이스 다이어그램](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%EC%9C%A0%EC%8A%A4%EC%BC%80%EC%9D%B4%EC%8A%A4%20%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8.png)


## 📌 시퀀스 다이어그램


![시퀀스 다이어그램](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%EC%8B%9C%ED%80%80%EC%8A%A4%20%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8.png)


## 📌 클래스 다이어그램


![클래스 다이어그램](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%ED%81%B4%EB%9E%98%EC%8A%A4%20%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8.png)


## 📌 논리적 데이터 베이스 모델링(ERD)


![논리적 데이터 베이스 모델링(ERD)](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_ERD.png)


## 📌 메뉴 구조도


![메뉴 구조도](https://github.com/jectgenius/wms-libra-track/blob/master/about/%EB%8F%84%EC%84%9C%20%EC%B0%BD%EA%B3%A0%20%EA%B4%80%EB%A6%AC%20%EC%8B%9C%EC%8A%A4%ED%85%9C_%EB%A9%94%EB%89%B4%20%EA%B5%AC%EC%A1%B0%EB%8F%84.png)


## 🎨 기능



### 🔆 주요 액터

---
#### ️🙋‍♂️ Admin User (WMS 관리자)
- 계정 관리, 창고 관리, 출판사 관리
#### 🦺 Inventory Manager (창고 직원)
- 계정 관리, 재고 관리, 입고 관리, 출고 관리, 구역 관리
#### 📚 Publisher Manager (출판사 직원)
- 계정 관리, 입고 요청, 입고 요청 조회, 출고 요청, 출고 요청 조회, 출판 관리

### 🎈 주요 기능

---
#### 🛑 회원 관리 
1️⃣ 회원 가입
- 출판사 매니저 가입 (insertPublisherMember)
- 창고 관리자 가입 (insertInventoryManager)
- 관리자 가입 (insertAdminUser)

2️⃣ 로그인 (loginCheck)

3️⃣ 사용자 인터페이스
- 출판사 매니저 메뉴 (choicePublisherMenu)
- 창고 관리자 메뉴 (choiceInventoryManagerMenu)
- 관리자 메뉴 (choiceAdminMenu)

---
#### 🙋‍♂️ 관리자 기능
1️⃣ 회원 관리 
- 회원 정보 조회 (findAdminUserInfo)
- 회원 정보 수정 (updateAdminUserInfo)

2️⃣ 출판사 등록
- 출판사 등록 (insertPublisherMember)

3️⃣ 회원 정보 관리
- 출판사 매니저 정보 조회 (findPublisherManagerInfo)
- 출판사 매니저 정보 수정 (updatePublisherManager)

4️⃣ 창고 관리
- 전체 창고 조회 (findAllInventory)
- 창고 코드로 창고 조회 (findInventoryByInventoryId)
- 창고 등록 (insertInventory)
- 창고 수정 (updateInventory)
- 창고 삭제 (deleteInventory)

---
#### 📚️ 출판사 직원 기능
1️⃣ 출판사 정보 관리
- 출판사 정보 조회 (findPublisherInformation)
- 출판사 정보 수정 (updatePublisher)
- 출판사 정보 삭제 (deletePublisherId)

2️⃣ 도서 관리
- 도서 등록 (insertBook)
- 도서 조회 (findAll)
- 도서 수정 (updateInformation)
- 도서 삭제 (deleteBook)
- ISBN 코드로 도서 검색 (findBookISBN)
- 도서 상세 정보 출력 (displayBook)
- 등록된 도서 목록 출력 (displayBookList)

---
#### 🦺 창고 직원 기능
1️⃣ 입고 관리
- 입고 요청 (insertInWarehousing)
- 입고 내역 조회 (findInWarehousingByStatus)
- 입고 상태 변경 (updateInWarehousingStatus)
- 입고 주문별 구역 배정 (reserveOrder)
- 입고 주문별 입하 처리 (completeOrder)
- 입고 내역 상세 조회 (findOrdersWithInWarehousingId)
- 입고 상태별 내역 조회 (findInWarehousingByStatus)
- 입고 주문별 구역 상세 조회 (findOrderAreaDetailByOrderId)

2️⃣ 출고 관리
- 출고 요청 (insertInWarehousing)
- 출고 내역 조회 (findInWarehousingByStatus)
- 출고 상태 변경 (updateInWarehousingStatus)
- 출고 주문별 구역 배정 (reserveOrder)
- 출고 주문별 출하 처리 (completeOrder)
- 출고 내역 상세 조회 (findOrdersWithInWarehousingId)
- 출고 상태별 내역 조회 (findInWarehousingByStatus)

3️⃣ 구역 관리
- 구역 조회 (findAllArea)
- 구역 상세 조회 (findAreaByAreaId)
- 창고별 구역 조회 (findAreaByInventoryId)
- 구역 등록 (insertArea)
- 구역 수정 (updateArea)
- 구역 삭제 (deleteArea)
- 구역 reserved 수정 (updateReserved)
- 창고 위치와 구역 이름으로 구역 조회 (findByLocationAndAreaName)
- 구역 상세 정보 출력 (displayArea)


## 😆 팀원 소개 및 소감


* 박민혁 - 출고
    * 신세계 inc에서 자바 교육을 받으며 많은 과제와 작은 프로젝트들이 있었지만 이번 미니 프로젝트를 하면서 많은것을 배우고 경험할 수 있었습니다. 
    * 팀원들과 함께 고민하며 요구사항 명세서를 도출하고 이를 바탕으로 유스케이스 다이어그램과 시퀀스 다이어그램을 작성하면서, 서비스를 기획할 때 여러가지로 고려해야할 부분이 정말 많다는 것을 느꼈습니다. 
    * 데이터베이스의 논리적 설계, 물리적 설계를 하면서 데이터베이스에 대하여 조금 더 깊게 이해할 수 있었고, 자바와 데이터베이스를 연동하여 코드를 작성하면서 실제로 데이터베이스를 어떻게 핸들링 하는지에 대하여 이해할 수 있었습니다. 
    * WMS 시스템이라는 주제로 MVC 기반의 개발을 진행하며 Model, View, Contorller 각각의 역할과 기능에 대하여 이해할 수 있었고 팀원들과 기능을 나눠서 개발하면 기능별로 독립적인 코드를 작성해 볼 수 있었습니다. 
    * 이번 협업을 진행하면서 개발 능력에 차이가 있음에도 불구하고, 원할한 의사 소통과 적극적인 도움으로 서로 부족한 부분을 매워주며 프로젝트를 완성할 수 있었습니다. 개발자에 대한 역량 평가에서 개발 능력뿐만 아니라 왜 의사 소통 능력도 중요하게 생각하는지 느낄수 있었습니다. 
    * 감사합니다.


* 박태준 - 회원관리
    * 수업시간에 짧게 배웠던 SQL, MYBATIS 지식을 이용해서 JAVA로 WMS 라는 프로그램을 개발하는 목표를 갖게되었습니다. 
    * 프로그램을 개발 한다는 것이 단순히 코드만 작성하면 되는 것 아닌가라는 단순한 생각을 가지고 있었습니다. 
    * 하지만 이 시스템에 대한 요구사항을 직접 도출하고 유스케이스 다이어그램, ERD, Class Diagram 을 작성하며 막막한 부분도 많았지만 이런 과정들 있음에 코드작성을 더 원활하개게 해줄 수 있음을 알게 되었습니다 
    * 이런 과정들을 통해서 팀원들과 소통하며 어떤 서비스를 개발할 때 소통능력과 흐름에 대한 이해도가 굉장히 중요할 것 같다는 생각이 들었고 소통을 하기 위해서는 개발에 대한 지식이 필요하다는 생각이 들었습니다 또한 아직 많이 미숙하다는 생각 또한 들었습니다. 
    * 이런 과정 후에 수업시간에 배운 MVC라는 패턴을 바탕으로 코드를 작성 하였습니다. 수업시간에 이론으로 설명듣고 코드를 따라 치며 어느정도 이해하고 있다는 생각이 들었습니다. 
    * 하지만 어떤 시스템을 구현하기 위해 직접 코드를 작성하는것은 이해를 하고 있었던 것이 맞는가 라는 생각이 들을 정도로 어려웠습니다. 또한 혼자 코드를 작성하는 것이 아니라 여러명의 팀원들과 같이 코드를 작성하는 것이기 때문에 나만 알아 볼 수 있는 코드가 아닌 다른 사람들이 알아보기에도 좋은 코드를 작성해야된다는 생각이 들었습니다. 
    * 이번 미니 프로젝트를 바탕으로 앞으로 보완해야할 점, 더 공부해야할 점에 대해 많이 생각이 들었으며, 팀원들과 소통하고 협업하며 이러한 의사소통 능력에 대한 중요성을 많이 배웠던 시간 이었던 것 같습니다. 
    * 뛰어난 팀원들에게 많은 도움을 받고 많이 배웠던 시간이었습니다. 언젠가는 팀원들처럼 남에게 배움을 줄 수 있는 개발자가 되고 싶다는 자극이 되었던 시간이었습니다. 감사합니다


* 🐯 심재람 - 창고관리 / 구역관리
    * 물류 산업 쪽에 평소에 큰 관심이 없었는데, 이번 팀 프로젝트를 통해 WMS라는 주제로 개발을 진행하면서 물류 도메인 지식을 공부하게 되어 유익했었습니다. 전혀 흥미가 없던 분야도 조금만 관심을 가지면 재미있는 지식들이 넘쳐난다는 것을 알게 되었던 것 같습니다. 
    * 팀원들이 평소에 WMS나 물류 산업에 대해 접해보지 않았다 보니, 프로젝트 기획을 위해서 요구사항을 도출할때 WMS가 뭔지 모르고 회의를 진행하게 되어서 전혀 다른 방향으로 요구사항을 도출하거나 서로 의견을 주고 받기 위해 의사소통을 하는 과정에서 어려움이 있었던 것 같습니다. 그래서, 하나의 주제에 대해 서로 생각하고 있는 것이 달랐던 것 같습니다. WMS에 대해서 강사님께서 요구사항 도출하기 전에 공부하라고 여러번 말씀하셔서, 별 다른 말이 없어도 팀원들이 당연히 공부 할 것이라고 생각했었는데, 다음 팀 프로젝트를 진행할 때는 팀원들과 다 함께 프로젝트 주제에 대해 먼저 공부를 하는 시간을 꼭 가져야 할 것 같다는 말을 할 것 같습니다. 또한, 협업하는데 의사소통이 얼마나 중요한지, 팀원들의 의견을 일치하거나 통일하는데 충분한 대화와 소통을 해야한다는 것을 느꼈습니다. 
    * 이번에 MVC와 MyBatis를 태어나서 처음 배우고 바로 팀 프로젝트에 활용하게 되었는데, 아무래도 배우자 마자 바로 팀 프로젝트에 적용하였기 때문에 매우 고통스러웠습니다. 기간이 워낙 짧다보니 당연히 조급해지고 조바심이 나서 복습을 하지 않고 바로 아무 생각 없이 IDE 부터 켜놓고 코드를 막 짜고 싶은 마음도 들었지만, 그래도 마음을 다잡고 일일 스크럼 회의때 팀원들에게 나는 복습이 필요할 것 같다고 먼저 양해를 구하고 나서 복습을 진행한 뒤 개발을 시작하였습니다. 그 덕분에 코드를 작성할 때는 큰 어려움 없었던 것 같습니다. 대신 짧은 프로젝트 기간에 대한 압박감 때문에 스트레스를 많이 받았던 것 같습니다. 
    * 이번 팀 프로젝트에서는 이전 프로젝트들과 달리 요구사항 명세서뿐만 아니라 유스케이스 다이어그램, 시퀀스 다이어그램등 문서 작업 산출물들을 많이 만들어야 했어서 실제 개발 시간보다 기획하고 문서 작업을 하는 부분에서 시간이 많이 소요되었던 것 같습니다. 또한, 포트폴리오인 ppt 파일도 만들었어야 해서 ppt 만드는데에도 담당자분들이 엄청난 시간을 쏟아 부었던 것 같습니다. 워낙에 작업해야되는 산출물들이 많다보니 평소에 항상 작성했던 리드미 파일도 신경쓰지 못했던 것 같습니다. 그래서 주객전도가 되어 오히려 개발에 많은 시간을 할애 하지 못했던 게 아쉬운 것 같습니다. 
    * MVC 패턴을 공부하면서 View단과 Controller단, Service단, Dao, Dto가 각각 어떤 역할을 하고 있는지 무슨일을 해야하는지 이해할 수 있었습니다. 
    * MyBatis에 대해 공부하면서 MyBatis는 사용하기위해 하는 설정들인 의존성 작성이나, mybatis-config.xml 파일 등 xml 파일들에 대한 이해나 사용법을 잘 아는 것이 핵심이라는 것을 알 수 있었습니다.

  
* 오형동 - 출판사관리
    * 이전 프로젝트에서는 팀원들이 원하는 주제를 정하고 바로 개발로 넘어갔습니다. 이번에 WMS라는 주제를 받았을 때, 들어본 적은 있지만 구체적으로 어떻게 동작하고 구현되는지 잘 몰랐습니다. 이번 미니 프로젝트에서 요구사항 상세 분석, 클래스 다이어그램, ERD CLOUD, 시퀀스 다이어그램 같은 문서 작업을 처음 접해봤기 때문에 어려움이 많았습니다. 서로 생각하는 기능과 원하는 기능이 달라서 어떻게 나아가야 할지 어려웠지만, 의사소통을 통해 문제를 해결하고 기능들을 정했을 때 보람을 느꼈습니다. 
    * 개발하면서 MVC 구조에 대해 알고 있다고 생각했지만, 놓치는 부분이 많았습니다. 코드를 작성하면서 모델은 무엇인지, 뷰 단에는 어떤 코드를 작성해야 하는지, 컨트롤러에는 어떤 코드를 작성하고 서비스 부분에서는 어떻게 비즈니스 로직을 작성할지 더 명확하게 구분할 수 있었습니다. 
    * 데이터베이스와 인텔리제이를 직접 연동하여 프로젝트를 구현하는 것은 처음이어서 데이터를 어떻게 전달하고, 외래 키와 연결된 테이블에 데이터를 어떻게 전달할지 고민이 많았습니다. 
    * 처음 프로젝트를 진행하면서 좋은 팀원들을 만나서 서로 의사소통이 잘 되어 원활하게 작업을 마무리할 수 있어서 좋았습니다.


* 우희민 - 입고 / 출고
    * 다소 생소한 주제를 프로젝트를 기획부터 구현까지 5명의 팀원들과 함께 진행하면서 서비스 개발의 단계들을 전체적으로 간략하기라도 경험해볼 수 있었습니다. 항상 주어진 상황에서의 개발에서 직접 요구사항이나 시퀀스 다이어그램처럼 기획을 하며 해당 문서 작업의 중요성을 알게 되었습니다. 
    * 처음으로 많은 팀원들과 프로젝트를 진행하면서 소통하며 팀원 안에서의 소통의 중요성에 대해서도 알게 되었습니다. 많은 팀원들이 같이 작업하여 하나의 서비스를 개발하기에 서로 조화를 잘 맞추어 작업하는 것이 중요하다고 느꼈습니다.


* 🐰 홍지민 - 회원관리
  * WMS 라는 재고 관리 시스템을 처음 접해봐서, 시스템 자체를 이해하는 것이 어려웠습니다. 시스템에 필요한 기능이 무엇이 있는지, 어떤 기능을 구현할 것인지 정하는 데까지 팀원 전체가 많은 의견을 주고 받았습니다. 프로젝트를 통해서 이용을 해보지 않았던 WMS 시스템을 공부해볼 수 있어서 좋았습니다. 
  * 프로젝트의 기능을 정했어도, ERD, USECASE, 시퀀스 다이어 그램, 클래스 다이어그램 등을 만들면서 요구사항이 잘 반영 되었는지, 직관적으로 체크할 수 있었습니다. 툴을 사용하는 방법도 더 익히면 원할할 것 같다고 생각해서 보완하고 싶습니다. 
  * 실제로 기능이 동작하는 코드를 직접 짜보는 것이 처음이라고 할 수 있어서 어려웠지만, 기능이 제대로 실행되었을 때 너무 뿌듯했습니다. MYBATIS도 사용하는 것이 익숙하지 않았는데 실제로 코드를 작성해보면서 사용법을 익히게 되는 계기가 되었습니다. 역시 직접 코드를 짜봐야 실력이 늘 수 있는 것 같다는 생각을 했습니다. 
  * 스캐너로 사용자의 입력 값을 받을 때, 타입이 맞지 않거나 올바른 값이 아닐 경우, 예외 처리를 했어야 했지만, 시간 상 구현하지 못한 점이 아쉬웠습니다. 다음 프로젝트를 할 때에는 예외 처리까지도 완벽하게 해보고 싶습니다. 
  * 하나의 메소드가 리턴되었을 때, 처리된 결과를 보여주고 싶어서 RESULT VIEW 클래스를 따로 만들었지만, 많이 활용하지 못한 아쉬움이 있습니다. 
  * 이번 프로젝트를 진행하면서, 사용했던 툴은 더 사용해보면서 익혀보고 싶고, 이번에 구현하지 못했던 기능들은 더 보완해서 구현해보고 싶습니다. 또한, 기능들이 제대로 실행되지 않을 때, 다들 잘 도와주셔서 감사했고, 여러가지 질문을 해도 다 들어주셔서 감사합니다…!!! 지금처럼 많이 부족했던 시절을 잊지 않고, 나중에 실무를 할 수 있을 정도의 실력을 갖춘다면 팀원분들 처럼 눈높이에 맞게 설명해줄 수 있는 사람이 되고 싶습니다!


## 🛠️ 라이선스
- 이 프로젝트는 MIT 라이선스에 따라 배포됩니다. 자세한 내용은 LICENSE 파일을 참고하세요.
