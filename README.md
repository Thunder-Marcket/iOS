##  Thunder Markect - 서버와 함께 번개장터 구현하기 
###### #iOS #소프트스퀘어드

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

### Used NetWork Method (POST : URLSession , GET : Alamofire)

##### Login View Controller

- 3.1 유저 로그인 /oauth/google (POST)

##### Timer Tab

- 2.1 오늘 공부기록 저장 /saveRecords/today (POST)

##### Follwer Tab

- 4.1 친구추가 /addFriend/\(follweeName) (GET)
- 4.3 친구 수 추가 /addNumberOfFollowers (POST)
- 4.4 친구 수 조회 /getNumberOfFollowers (GET)

##### Market Tab

##### Profile Tab

- 1.1 유저 정보 조회 /showMember (GET)
- 2.2 월별 공부내역 조회 /records/monthly?month=08 (GET)

---

### 🙇‍♂️ Team Member
##### iOS 
- 소이 / 이주송 
##### Server
- 시오 / 정혜선
- 찰리 / 김진수

---

### 🧑‍💻 Ref. link


