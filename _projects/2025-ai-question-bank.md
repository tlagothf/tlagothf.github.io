---
title: "LMS 기반 AI 문제은행 자동 생성 기능"
excerpt: "LangChain + GPT + Flask API로 문제은행 자동 생성"
layout: single
---

**기간:** 2025.03.01 ~ 2025.07.15  
**소속:** ㈜아이티원즈, 3인 팀

### 개요
LMS 학사관리 시스템에서 교과 내용을 입력하면  
AI가 객관식·주관식 문제를 자동 생성해 문제은행에 저장하는 기능 개발.

### 역할 및 기여

- Java/JSP 기반 학사 시스템에서 문제은행 생성 화면 및 로직 설계·구현  
- LangChain 기반 Python 모듈 개발:  
  - PromptTemplate로 문제 유형별 프롬프트 체계화  
  - OutputParser로 GPT 응답을 JSON 형태로 구조화  
- Flask API 서버 구성 및 Java ↔ Python 연동 처리  
- 생성된 문항을 MySQL 문제은행 테이블에 저장하고 관리자 검수 기능 제공

### 기술 스택

`Java`, `JSP`, `MyBatis`, `JavaScript`,  
`Python`, `LangChain`, `OpenAI API`, `Flask`, `REST API`, `MySQL`

### 성과

- 수작업 대비 문제 생성 시간 약 80% 절감  
- 실제 운영 중인 학사 시스템에 AI 기능을 연동해 실무 활용 가능성 입증  
- 프롬프트 템플릿 구조화로 문제 유형·형식·난이도 관리가 용이해짐  
