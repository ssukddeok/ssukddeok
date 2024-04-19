# 반려견 보험 비교 챗봇
### 반려견 보험 선택을 도와주는 4가지 보험사(현대해상다이렉트, 삼성화재, DB손해보험, KB손해보험) 비교 챗봇

---
# 📋 Contents
## 1. 프로젝트 소개 
- 목표
- 수행 기간 및 팀원
- repo structure
- Project Workflow

  
## 2. 상세 task

- LLM 모델 테스트
- Frontend
- Backend
- LangChain
  
## 3. 결과

## 4. 프로젝트 회고
### 어려웠던 점
### 배운 점
### 보완할 점

---
## 1. 프로젝트 소개 
### : LangChain을 이용한 App 개발 PJT(이어드림 4기) 
#### 반려견 양육가구 400만시대(2023년 한국 반려동물보고서) 반려견을 위한 보험을 위한 수요 증가함.
#### 보장 내용과 가격을 비교하는 챗봇을 구현 

#### 목표 : 반려견을 보험 선택을 도와주는 4개 보험사 비교와 보장범위 축약
(사진) (사진2)
#### 수행 기간 및 팀원 :  
- 📆 수행기간: 2024.04.17 ~ 2024.04.19
- 팀원:
  
| 강상우  | 송유창  | 신윤재  | 이유진  | 이진선  | 이진아  |
|--------|--------|--------|--------|--------|--------|
| ![Avatar 1](https://avatars.githubusercontent.com/u/160104734?v=4)| ![Avatar 2](https://avatars.githubusercontent.com/u/87472756?v=4)| ![Avatar 3](https://avatars.githubusercontent.com/u/140726268?v=4) | ![Avatar 4](https://avatars.githubusercontent.com/u/95261468?v=4)| ![Avatar 5](https://avatars.githubusercontent.com/u/166676809?v=4)| ![GitHub Avatar](https://avatars.githubusercontent.com/u/166089376?v=4) |
| [Github](https://github.com/allenkang92) | [Github](https://github.com/hindernislauf) | [Github](https://github.com/yoonjaeo)| [Github](https://github.com/Developer-Yujin)| [Github](https://github.com/Jinsun577)| [Github](https://github.com/ssukddeok) |
#### repo structure : 
#### Project Workflow 
#### (→ 자동으로 서브 주제 생성 → 서브 주제 선택 → 최종 스크립트 생성 및 출력

## 2. 상세 task

#### LLM 선정 모델
- 목표
  - 원하는 내용/보장 범위/충분한 분량이 생성 가능한 LLM 모델 선정
  - LLM 모델에 맞는 최적 프롬프트 도출

- LLM 선정 모델 
  - gemini pro

#### Frontend
- UI 기획
  - 메인 주제 입력창
  - 서브 주제 생성 버튼
  - 서브 주제 표시 화면
  - 스크립트 생성 버튼
  - 스크립트 표시 화면

#### Backend
- Streamlit로 웹 애플리케이션 구축
사용자의 입력을 받아 처리하며, 그 결과를 HTML 템플릿에 전달하여 동적인 웹 페이지를 생성
서브 주제 표시 버튼과 스크립트 생성 버튼이 눌렸을 때, 사용자의 입력 및 선택된 옵션에 따라 동적으로 서버 측 로직을 수행
로직: 프롬프트와 LLM으로 구성된 LangChain을 invoke

#### LangChain
- Chat model : Gemini-pro

- 

## 3. 결과

## 4. 프로젝트 회고

## 어려웠던 점
## 배운 점
## 보완할 점
