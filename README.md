# 반려동물을 위한 앱 "댕묘댕"
-2023년 2학기 경동대학교 컴퓨터공학과 졸업작품

![danglogo](https://github.com/1924023/parkjeonghyun/assets/143380674/55836122-52db-4050-8de5-36ad02a8a909)

## 팀구성
팀장: 박정현


팀원: 조승연, 홍순호

## 목차
### 1. 소개
* 앱 소개
* 주제를 선정하게 된 이유
* 주요 적용 기술
* 구조
* 간략한 기능 설명
  
### 2. 실용성
### 3. 시장성
### 4. 기대효과
### 5. 결론
---

## 1. 소개
### 앱소개
![danglogo](https://github.com/1924023/parkjeonghyun/assets/143380674/55836122-52db-4050-8de5-36ad02a8a909)

이 어플리케이션은 총 7가지의 기능을 제공한다.

* 캘린더를 이용한 일정기록
* GPS를 이용한 주변 서비스(장소) 검색
* GPS를 이용한 산책 기록 및 관리
* YouTube API를 통해 가져온 훈련영상 시청
* 공공데이터포털 유기동물 API를 통해 유기동물 목록 조회
* 자신의 반려동물을 자랑할수 있는 커뮤니티
* 반려견 기초 예방접종 및 주의 음식종류, 질병, 응급처치 방법 제공
---
### 주제를 선정하게 된 이유

많은 미디어 매체에서는 반려동물 관련 콘텐츠를 방영하고, SNS에서는 전용 계정이 생기는 등 반려동물에 대한 관심이 뜨겁다. 하지만 SNS의 광고나 무분별한 게시글로 피로를 느껴, 관심 있는 분야만 즐길 수 있는 플랫폼을 찾는 사용자가 증가하고 있다. 이에 반려동물에 집중한 커뮤니티(SNS)와 반려동물 케어에 도움이 되는 기능을 갖춘 ‘댕묘댕’ 애플리케이션을 개발하게 되었다.

---

### 주요 적용 기술
---

#### 개발언어: Kotlin, SQL
---

#### 개발도구:  Android Studio
---

##### 개발환경: Amazon EC2, Amazon RDS, MariaDB, Nodejs
---

##### 주요기술: REST API
---

### 구조

---
### 간략한 기능 설명
---
#### 1. 홈 화면
![홈화면](https://github.com/1924023/parkjeonghyun/assets/143380674/581f0c20-966d-4156-8c15-f910fb518635)
* 각 기능으로 이동할수 있는 버튼
* 사용자의 이름 표시
* 일정기록에 기록된 알람 확인 버튼
---
#### 2. 일정기록
![일정기록](https://github.com/1924023/parkjeonghyun/assets/143380674/f02db5c9-731f-4d81-a12c-a2beb0829002) ![일정기록1](https://github.com/1924023/parkjeonghyun/assets/143380674/37013697-c590-4487-bc35-e3526c9d6335)
* 캘린더에 일정을 기록
* 일정에 맞게 알람기능

---
#### 3. 동반시설 탐색
![동반시설1](https://github.com/1924023/parkjeonghyun/assets/143380674/caf17018-0b17-4550-ad2d-809e7a1099e6)![동반시설](https://github.com/1924023/parkjeonghyun/assets/143380674/b7cfbf01-abd0-48dd-aa5f-b98b23996017)
* 사용자 위치기반 3km 이내 동반시설 제공
* 해당 시설 상세정보 제공
---
#### 4. 훈련
![훈련](https://github.com/1924023/parkjeonghyun/assets/143380674/6c65bc09-6352-4ba5-92e6-461da2323597)![훈련1](https://github.com/1924023/parkjeonghyun/assets/143380674/bd8d3f48-9396-4248-9899-4fbb5a1fa834)
* 각 훈련영상 카테고리
* 훈련영상 제공
---
#### 5. 유기동물 입양
구현중
---
#### 6. 커뮤니티
구현중
---
#### 7. 산책기록
![산책](https://github.com/1924023/parkjeonghyun/assets/143380674/509ba697-4134-415b-a4ff-2330e6611255)
* 사용자 이동경로 라인으로 표시 이동거리, 속도, 운동시간 DB에 저장
---

## 2. 실용성

* 사람들은 한 공간에서 모든 일들을 해결 하는 것을 추구하는 경향이 있다. 예를 들어, 상점, 운동 시설, 도서관 등 우리가 생각할 수 있는 웬만한 것들은 아파트 단지안에서 이용 할 수 있다.
이와 같이, 사람들은 수 많은 기능과 서비스를 하나의 애플리케이션에서 이용하길 원한다.
* 댕묘댕은 반려동물의 건강정보, 유기동물 탐색, 산책 기록 및 장소 검색 등 다양한 기능을 통해서 반려동물에 집중 할 수 있는 환경과 반려동물 케어에 도움을 주기에 반려가구에 유용하게 자주 쓰일 것이다.

## 3. 시장성

* 반려가구 구성원들의 나이 스펙트럼 다양하기 때문에 넓은 수요층을 가질 수 있다.
* 기반은 SNS(커뮤니티) 및 위치 기반 서비스이기 때문에 지속적으로 추가 개발이 가능하다.
* 개인화된 서비스이기 때문에, 사용자 데이터를 체계적으로 관리할 수 있다.

## 4. 기대효과

#### * 편의성
  
  산책 기록 및 관리, 장소 검색 및 저장 기능을 한 애플리케이션에서 손쉽게 이용 가능

#### * 유기동물 감소

  유기동물 입양 탭을 통하여 유기동물에 대한 관심도 상승으로 감소효과 기대

## 5. 결론

아직 진행중.
