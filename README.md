## ⚡️ Thunder Market - 서버와 함께 번개장터 구현하기 
###### #iOS #(주)소프트스퀘어드

### 📱 Final Result

https://www.youtube.com/watch?v=N5Q3t-rW-aA

---

### 🧠 Gotten & Used Stack (중복제외)

- Templete 맞추어 Story Board 분할하기(View와 Controller를 구분) - [ref.](https://swieeft.github.io/2020/02/24/StoryboardReference.html)
 
- Bottom Sheet - [ref.](https://gonslab.tistory.com/57)
 
- Horrizental ScrollView 
 
- Tabman(scrollToIndex)
 
- CollectionView & Timer로 2초에 한번씩 배너광고가 페이징되게 구현 - [ref.](https://gonslab.tistory.com/24)

- Tabman Delegate (should Select) - [ref.](https://stackoverflow.com/questions/33837475/detect-when-a-tab-bar-item-is-pressed)

- Single Ton Pattern(Configuration Folder)
 
- URL로 Image 가져오기 - [ref.](https://hongssup.tistory.com/158)
 
- Data Model(Collection View, Table View)
 
- Collection View Cell 화면전환(Delegate X)

- Table View Section Header - [ref.](https://hururuek-chapchap.tistory.com/153)

- Constraint with IBOulet

---

### 🕸 Used NetWork Method (POST : URLSession , GET : Alamofire)

1. Users
  * 1.1 전화번호로 회원가입
  * 1.2 전화번호로 로그인
  * 1.5 마이페이지 유저 정보 가져오기 

2. Items 
  * 2.4 상품 목록 가져오기(최신순)
  * 2.6 상품 상세 사항 가져오기(최근 본 상품도 생성)

3. SaleViews
  * 3.1 최근 본 상품 조회

4. Address
  * 4.1 배송지 정보 추가
  * 4.2 배송지 정보 가져오기

5. Likes
  * 5.1 찜 목록 조회
  * 5.2 상품 찜/찜 해제

7. Searches
  * 7.3 검색 페이지 조회(최근 검색어, 추천 브랜드)

8. Brands
  * 8.1 브랜드 모두 가져오기
  * 8.2 브랜드 검색하기(최근 검색어에 안들어감)
  * 8.3 내가 팔로우 한 브랜드 목록 가져오기

10. Chats
  * 10.3 번개톡 채팅방 전부 가져오기

12. Orders
  * 12.1 택배 거래시 필요한 데이터 가져오기
  * 12.3 거래 등록
  * 12.4 거래내역(구매) 조회

13. Payment
  * 13.1 결제 수단 등록
  * 13.2 결제 수단 조회 

 15 Brand Follow
  * 15.1 브랜드 팔로우/언팔로우

---

### 🙇‍♂️ Team Member
##### iOS 
- 소이 / 이주송 
##### Server
- 시오 / 정혜선
- 찰리 / 김진수

---

### 🧑‍💻 Ref. link

- Tabman Library
    - [[iOS] TabMan library (+View에 넣기)](https://velog.io/@0inn/iOS-TabMan-library-View%EC%97%90-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0)
    - [[iOS/Swift] TabMan 라이브러리 사용하기 - (Custom tabbar / 상단 탭바 / 커스텀 탭바)](https://vanillacreamdonut.tistory.com/259)
    - [Tabman Github 공식문서](https://github.com/uias/Tabman)
    - [탭맨 라이브러리 예제 및 커스텀 방법](https://developer-p.tistory.com/161)

- section header custom
    - [참고자료](https://duwjdtn11.tistory.com/560)
    - [section으로 나누어진 UITableView 만들기](https://calmone.tistory.com/entry/iOS-UIKit-in-Swift-4-section%EC%9C%BC%EB%A1%9C-%EB%82%98%EB%88%84%EC%96%B4%EC%A7%84-UITableView-%EB%A7%8C%EB%93%A4%EA%B8%B0)
    - [Changing Font Size For UITableView Section Headers](https://stackoverflow.com/questions/19802336/changing-font-size-for-uitableview-section-headers)
    - [TableView Cell의 selection 관리하기](https://velog.io/@yongchul/iOSTableView-Cell%EC%9D%98-selection-%EA%B4%80%EB%A6%AC%ED%95%98%EA%B8%B0)
    
- 타입 캐스팅
    - [[swift] 스위프트의 다운 캐스팅 옵션 : as? 입력 또는 as! 유형?](http://daplus.net/swift-%EC%8A%A4%EC%9C%84%ED%94%84%ED%8A%B8%EC%9D%98-%EB%8B%A4%EC%9A%B4-%EC%BA%90%EC%8A%A4%ED%8C%85-%EC%98%B5%EC%85%98-as-%EC%9E%85%EB%A0%A5-%EB%98%90%EB%8A%94-as-%EC%9C%A0%ED%98%95/)
    - [Swift) is, as - 타입 캐스팅 (Type Casting)](https://babbab2.tistory.com/127)

