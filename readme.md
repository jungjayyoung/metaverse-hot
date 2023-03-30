# 김종섭 작업 로그

## 2023.03.20

### 1. 업무일지

- 팀 미팅 
  - 프로토타입 리뷰 및 방향성 회의
  - 구현 기능 우선도 정립

### 2. 개발일지
 - 스테이지 1 맵 제작
     - 몬스터 path 재구현
     - 맵 디자인
     - 오브젝트 충돌 구현 (w. 재영)
     - 낚시를 위한 중립 건축물 구현

![image](https://user-images.githubusercontent.com/104764340/226290449-1bc2ed8b-0ee4-4b5f-ab29-04dc210c92c7.png)


## 2023.03.21 

- 팀 미팅 
  - 팀 전체 코드 확인
    - Tower : public 변수명 중복 확인
    - Enemy : 주석 잘달고 깔끔함!
    - Character : 주석만 좀더 있으면 좋을것 같음
  - UI 기획서 확인 후 피드백

### 개발일지

 - 스테이지 1,2 맵 제작
     - 스테이지 2 맵 디자인
     - 낚시를 위한 중립 건축물 구현
     - 시점 및 건물 투명화 (구현중)
     - 
 - 백엔드 서버 구조 빌드 (진행중)
     - w. 해석
     - 스프링부트 초기 디렉토리 및 파일 테스팅
     
![image](https://user-images.githubusercontent.com/104764340/226557075-869220df-b4b0-4593-a4ca-b0941bbbe511.png)

## 2023.03.22

### 2. 개발일지

 - Version 2.0 메인 Scene merge
     - 현재 완료부분
       - 몬스터 : 간단한 에셋, 
       - 타워 : 랜덤 공격 & 디버프 타워 구현
       - UI : 연동된부분 없음 , 디자인만 먼저 제작 (GameManager 리팩토링중)
       - 멀티플레이 : 플레이어 동기화 완료, 포탑 및 게임매니져 디버깅중
     
 - 스테이지 1,2,3 맵 제작
     - 유저 이동하며 통과버그 있는지 확인
     - 몬스터 Path 제작 (Stage 1)
     
![image](https://user-images.githubusercontent.com/104764340/226850838-3d8025a4-1076-4c3f-bd06-9bfea783c2ff.png)


## 2023.03.23


### 1. 업무일지

 - 컨설턴트님 미팅 & 전문가 미팅 준비
   - 메인 씬 머지 및 디버깅
   - 멀티플레이 및 몬스터 사냥 테스팅

### 2. 개발일지
     
 - 스테이지 1,2,3 기믹 추가
     - 무트코인 밭 추가
     - 은행, 상점, 햄버거가게 건물 추가
     - AI Integration 도입중
 - 전체 코드내역 확인 (진행중)

 ## 2023.03.24


### 1. 업무일지

 - 주간 스크럼
   - 개인별 회고
   - 다음주 부터 UI 및 사운드에 추가 투입할 예정

### 2. 개발일지
     
 - 백앤드 서버 구축
    - Springboot
    - 유니티와 연동 테스트 확인
 - 로그인 및 기본 유저 API 제작
    - Login - 로그인 시 유저 정보 가져오기 [GET]
    - duplicate check - 닉네임 및 이메일 중복검사 [POST]
    - signup - 회원가입 시 닉네임과 firebase ID DB에 저장 [POST]



## 2023.03.27


### 1. 업무일지

 - 주간 스크럼
   - 파트별 담당업무 회고 및 병목현상 해결
     - 종섭 : UI 에 투입
 - 팀장미팅

### 2. 개발일지
     
 - 백앤드 서버 구축
    - ERD 리팩토링
    - 엔티티 구축 및 연동확인
 - 로그인 및 기본 유저 API 제작
    - Login - 로그인 시 유저 정보 가져오기 [GET]
    - duplicate check - 닉네임 및 이메일 중복검사 [POST]
    - signup - 회원가입 시 닉네임과 firebase ID DB에 저장 [POST]
 - UI 구조 확인 및 개인공부


## 2023.03.28 [화]


### 1. 업무일지

 - 팀원 개별면담 : 서영준
 - UI 및 GameManger 관련 코드리뷰
   - UI : UI 작업리스트 만들기 및 현황파악 (w. 영준)
   - GM : 코드 전체리뷰 (w. 희연)

### 2. 개발일지
     
 - 기본 UI (Top Left) 연동
    - Text GetComponent 처리
    - UI 화면 표시
 - Tower 디버깅 (w. 정규)
 - UI 구조 확인 및 개인공부

 ## 2023.03.29 [수]


### 1. 개발일지
     
 - 기본 UI (Top Left) 연동
    - Text GetComponent 처리
    - Tower, 주식 추가
 - Event 구현
    - 강화 아이템 상점
    - 햄버거 가게
    - 주식 거래소
    - 장승 (w.정규)
    - 알약이
 - 유저 및 타워 스테이터스 구현
    - 기본스텟 / 강화스택 / 계정스택 / 버프 스택
    - 합연산으로 적용


## 2023.03.30 [목]


### 1. 개발일지
     
 - 기본 UI 연동 및 Event 구현
    - UI 를 통한 스테이터스 변화 및 아이템 구입 구현완료
      - 강화 아이템 상점 - 유저 스테이터스와의 연동
      - 햄버거 가게
      - 주식 거래소(w.정규) - UI 와 이벤트 연동
      - 장승 (w.정규) - UI와 이벤트 연동
      - 알약이
 - 유저 및 타워 스테이터스 구현
    - 기본스텟 / 강화스택 / 계정스택 / 버프 스택
    - 코드 디버깅
    - 강화 후 스택 적용 테스팅