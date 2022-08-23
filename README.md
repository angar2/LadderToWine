# Ladder to Wine

## 1. 프로젝트 정보
> 개발 기간: 2022.06.02 ~ 2022.06.13

> 팀원: 엄관용, 나성근, 이동현, 한건희

## 2. 사용 기술
> Python 3  
> Django 4.0.5  
> MySQL  
> pandas 
> numpy  

> HTML
> CSS

## 3. 기획 및 설계
> ### ERD 설계
> ![image](https://user-images.githubusercontent.com/100769423/186102056-72ff767a-d377-408f-b5e6-7cc8cb922b78.png)

> ### Mock-up
> ![image](https://user-images.githubusercontent.com/100769423/186102543-9619950e-9161-4ef1-bace-882d7e03174c.png)

> 데이터
> [캐글] https://www.kaggle.com/code/dev7halo/similarity

## 4. 핵심 기능
### 와인 추천
### 와인 상세정보
### 와인 리뷰 작성
### 와인 별점 평가
### 와인 찜하기
### 회원가입 및 로그인

## 5. 트러블 슈팅
### 핵심
#### 와인 이미지
- 사용하는 csv 와인 데이터에 와인 이미지가 포함되어 있지 않음
- 실제 와인 서비스 사이트에서 와인 이름으로 이미지 주소를 크롤링
- 모든 이미지 주소를 크롤링하기에 크롤링 지식 및 시간적 문제 발생
- 데이터를 미리 가지고 있는 방식이 아닌 실시간으로 해당 와인 이미지 주소를 크롤링

- 그 외
