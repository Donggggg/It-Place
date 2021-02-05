# SW 중심대학 해커톤
## It-Place
코로나 이슈로 대면 만남이 어려워진 언택트(Untact) 시대.
각자의 공간에서도 친밀감을 형성하고, 추억을 쌓을 수 있는 새로운 방안을 제시합니다.

잇플이  현제 제공하는 서비스는
- ...
- ...
과 같은 서비스 등이 있고, 향후 ... 를 제공할 예정입니다!

## 현황
---
- 2021 SW중심대학 공동해커톤 산출물
- 개발기간: \`21.02.04 ~ \`21.02.06

김소령(서울여자대학교, 디자이너, 팀장)
김동규(숭실대학교, 백엔드)
정선아(충북대학교, 백엔드)
이도현(한양대학교, 프론트)
이범준(호서대학교, 백엔드)

## 개발 배경
---
코로나 이후로 우리는 더 이상 한 공간에 모이기 조차 조심스럽게 되었습니다.

사람들은 소통을 위한 대안으로 온라인 화상 채팅 앱을 사용하기 시작했고, 이제는 다양한 모임의 성격에 맞는

맞춤형 커뮤니티 서비스가 필요해졌습니다. 이에 각 모임의 특성에 맞는 기능을 반영한 '잇-플'을 기획하였습니다.

### 개발 문서
---
###### 초기구상
...

---

###### 초기목표
...

---

###### 기술스택
Flutter

...

---

###### 백엔드
- RESTful API
- ...

###### 프론트엔드
- Provider Design Pattern
- ...

###### 참고자료
- ...


### 향후 계획
---
###### 1. 프로젝트 관련
...

###### 2. 서비스 관련

### 최종 목표
---
- ...

### 정보
---
###### 컴퓨터 구성 / 필수 조건 안내 (Prerequisites)
- Node.js(예시)
- Recommende Chrome

###### 설치 안내 (Installation)
- ...
###### 사용법 (Getting Started)
- ...
###### 저작권 및 사용권 정보 (Copyright / End User License)
- MIT License

###### 배포자 및 개발자의 연락처 정보 (Contact Infomration)
- leedh2008@naver.com
###### 알려진 버그 (Known Issue)
- ....
###### 문제 발생에 대한 해결책 (Troubleshooting)
- ....
###### 크레딧 (Credit)
- ....
###### 업데이트 정보 (Change Log)
- `21.02.04 0.0.1

### 스크린샷
---
...

## Git 관리 방법

팀원들끼리의 협업을 위해 git-flow 약식 모델을 사용하였습니다.

1. Issue 생성
> Issues -> New issue

2. 이슈번호 생성이 되면 Feature 브런치 작성
```
$ git branch feature/#1
```

3. 개발은, 해당 브런치에서 작업
```
git checkout feature/#1
```

4. 개발 완료시 해당 브런치에 푸쉬
```
git commit -m "... 구현완료 #1"
git push origin feature/#1
```

5. develop 브런치에 merge하기 위해 Pull requests 작성 

> Pull requests > New pull requests 
feature/#1을 develop으로 merge 요청 후 수락

