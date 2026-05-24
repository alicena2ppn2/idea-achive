# idea archive

우주 속에 흩어진 아이디어들을  
별처럼 저장하고 이어가는 감성 아카이브.

---

## About

**idea archive**는 떠오른 아이디어를  
감성적인 인터랙션과 함께 기록하는 웹 아카이브입니다.

사용자는 하나의 아이디어를 입력하면  
AI가 핵심 키워드를 추출하고,  
기존 아이디어와의 연결성을 찾아  
우주 속 오브 형태로 저장합니다.

단순 메모장이 아니라,  
아이디어들이 서로 이어지고 떠다니는  
하나의 작은 우주를 만드는 것이 목표입니다.

---

# Main Features

## 1. Intro Screen

- 우주 배경 애니메이션
- 중앙 핑크 스타버스트
- 반짝이는 별 효과
- 스크립트 폰트의 `idea archive`
- `"아이디어 저장소 가기"` 버튼

---

## 2. Archive Screen

### Space Transition

첫 화면에서 저장소로 진입할 때  
우주 속으로 들어가는 듯한 트랜지션 효과를 제공합니다.

### Orb Roadmap

- 세로 스크롤 기반 로드맵
- 오브들이 위로 펼쳐지는 구조
- 최신 아이디어가 가장 아래 배치

### Orb System

- 오브는 3개의 이미지 중 랜덤 생성
- 오브 겉면은 완전히 불투명
- 클릭 전까지 내용 확인 불가
- 클릭 시:
  - 내용 보기
  - 수정
  - 삭제 가능

---

## 3. Input Screen

### Idea Writing

사용자가 자유롭게 아이디어를 입력할 수 있습니다.

### AI Keyword Floating

입력을 잠시 멈추면:

- OpenAI API 기반 키워드 추출
- 핵심 키워드가 주변에 둥실 떠다님
- 기존과 비슷한 아이디어가 작은 오브 형태로 등장

### Finish Animation

`Finish` 버튼 클릭 시:

- 오브가 위로 두둥실 떠오르며 저장
- 저장 후 로드맵에 자동 추가

---

# AI Features

Using:

- OpenAI API

Functions:

- 키워드 추출
- 유사 아이디어 탐지
- 아이디어 연결성 분석

---

# 🛠 Tech Stack

## Frontend

- React
- TypeScript
- Tailwind CSS
- Framer Motion

## Backend

- Node.js
- Express

## Database

- MongoDB

## AI

- OpenAI API

---

# Design Keywords

- dreamy
- cosmic
- emotional UI
- floating motion
- soft glow
- archive universe


---

# Goal

아이디어는 순간적으로 떠올랐다가 사라집니다.

**idea archive**는  
그 순간들을 우주 속 별처럼 저장해  
사용자만의 감성적인 아이디어 은하를 만드는 프로젝트입니다.
