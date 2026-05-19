---
layout: single
title: "Data Analysis Portfolio"
permalink: /data-portfolio/
author_profile: false
---

<style>
.masthead,
.author__avatar,
.author__content,
.author__urls-wrapper {
  display: none !important;
}

.page {
  max-width: 980px;
  margin: 3rem auto;
}

.hidden-portfolio-nav {
  display: flex;
  gap: 1.2rem;
  margin-bottom: 2.5rem;
  padding: 1rem 1.2rem;
  background: #0b1120;
  border-radius: 14px;
}

.hidden-portfolio-nav a {
  color: #ffffff;
  font-weight: 700;
  text-decoration: none;
}

.hero-title {
  font-size: 2.2rem;
  margin-bottom: .8rem;
}

.hero-sub {
  font-size: 1.05rem;
  color: #4b5563;
  line-height: 1.8;
}

.portfolio-section {
  margin-top: 3rem;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.2rem;
  margin-top: 1.2rem;
}

.info-card {
  background: #ffffff;
  border-radius: 16px;
  padding: 1.4rem 1.5rem;
  box-shadow: 0 10px 25px rgba(15,23,42,0.08);
}

.info-card h3 {
  margin-top: 0;
  font-size: 1rem;
}

.info-card p {
  color: #4b5563;
  font-size: .9rem;
  line-height: 1.7;
}

.badge {
  display: inline-block;
  padding: .35rem .7rem;
  margin: .25rem;
  border-radius: 999px;
  background: #eef2ff;
  color: #1e3a8a;
  font-size: .85rem;
  font-weight: 700;
}
</style>

<nav class="hidden-portfolio-nav">
  <a href="#about">About</a>
  <a href="#experience">Experience</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
</nav>

<section id="about">

# Data Analysis Portfolio

안녕하세요.  
저는 **Java 백엔드 개발 경험을 바탕으로 데이터와 AI를 함께 다루는 개발자 심해솔**입니다.

백엔드 개발을 하면서 단순히 기능을 구현하는 것뿐 아니라,  
데이터가 어떤 흐름으로 저장되고 활용되는지,  
그리고 그 데이터를 어떻게 서비스 개선으로 연결할 수 있는지에 관심을 갖게 되었습니다.

현재는 Java/Spring 기반 개발 경험과 Python 기반 데이터 처리 경험을 함께 쌓으며,  
향후 데이터 분석과 AI 서비스 개발 역량을 더 깊게 확장하고자 합니다.

</section>

---

<section id="experience" class="portfolio-section">

## 제가 가진 강점

<div class="card-grid">

<div class="info-card">
<h3>서비스를 이해하는 개발자</h3>
<p>단순 코드 구현보다 사용자가 어떤 흐름으로 서비스를 이용하는지, 데이터가 어떤 의미를 가지는지 함께 고민합니다.</p>
</div>

<div class="info-card">
<h3>데이터 처리 경험</h3>
<p>Python, Pandas, Selenium, MySQL 등을 활용해 데이터를 수집하고 정리하며 분석 가능한 형태로 가공한 경험이 있습니다.</p>
</div>

<div class="info-card">
<h3>AI 기능 연동 경험</h3>
<p>LangChain, OpenAI API, Flask를 활용해 Java 시스템과 AI 기능을 연동한 경험이 있습니다.</p>
</div>

<div class="info-card">
<h3>끝까지 해결하는 태도</h3>
<p>오류가 발생했을 때 로그와 데이터 흐름을 추적하며 원인을 찾고, 기능이 실제로 동작할 때까지 개선하는 편입니다.</p>
</div>

</div>

</section>

---

<section id="skills" class="portfolio-section">

## 사용해 본 기술

<span class="badge">Java</span>
<span class="badge">Spring</span>
<span class="badge">JSP</span>
<span class="badge">MyBatis</span>
<span class="badge">Python</span>
<span class="badge">Pandas</span>
<span class="badge">Selenium</span>
<span class="badge">BeautifulSoup</span>
<span class="badge">Scikit-learn</span>
<span class="badge">Kiwi</span>
<span class="badge">FastText</span>
<span class="badge">LangChain</span>
<span class="badge">OpenAI API</span>
<span class="badge">Flask</span>
<span class="badge">MySQL</span>
<span class="badge">MSSQL</span>
<span class="badge">PostgreSQL</span>

</section>

---

<section id="projects" class="portfolio-section">

## 주요 경험

### 1. 사용자 맞춤형 영화 추천 프로그램

Python을 활용해 영화 데이터를 수집하고,  
형태소 분석과 임베딩 기반 유사도 분석을 통해 추천 로직을 구현했습니다.

- Selenium 기반 데이터 수집
- JSON 데이터 파싱
- Kiwi 형태소 분석
- FastText 임베딩
- 유사도 계산 기반 추천
- MySQL DB 설계 및 연동

이 프로젝트를 통해  
데이터 수집 → 전처리 → 분석 → 추천 결과 도출의 흐름을 경험했습니다.

---

### 2. AI 기반 문제은행 자동 생성 기능

LMS 시스템에서 교과 내용을 입력하면  
GPT 기반으로 객관식/주관식 문제를 자동 생성하는 기능을 개발했습니다.

- LangChain PromptTemplate 구성
- OutputParser 기반 JSON 응답 가공
- Flask API 서버 구성
- Java 시스템과 Python AI 모듈 연동
- 생성 결과를 문제은행 DB에 저장

이 경험을 통해  
AI 응답을 실제 서비스에서 사용할 수 있는 데이터 구조로 변환하는 과정을 배웠습니다.

---

### 3. GPT 기반 챗봇 기능 개발

사용자가 질문을 입력하면 GPT 기반 챗봇이 응답하는 기능을 개발했습니다.

- LangChain 기반 대화 흐름 구성
- GPT API 연동
- Flask 서버와 Java/JSP 화면 연동
- 사용자 질의 로그 저장
- 응답 포맷 및 통신 오류 디버깅

단순 챗봇 구현을 넘어,  
사용자 입력과 응답 데이터를 어떻게 안정적으로 처리할지 고민한 경험입니다.

---

### 4. 백엔드 성능 개선 경험

전기차 서비스 백엔드에서 PostgreSQL 기반 조회 성능 개선을 경험했습니다.

- 느린 쿼리 분석
- 인덱스 추가
- SSE 및 조회 API 성능 개선
- 기존 API 구조 리팩터링

이 경험을 통해  
데이터베이스 구조와 쿼리 설계가 서비스 품질에 직접적인 영향을 준다는 점을 체감했습니다.

</section>

---

<section class="portfolio-section">

## 앞으로의 방향

저는 앞으로 **데이터를 이해하는 백엔드 개발자**,  
그리고 **서비스 데이터를 분석해 개선 방향을 제안할 수 있는 개발자**로 성장하고 싶습니다.

아직 데이터 분석 실무 경험이 깊은 단계는 아니지만,  
Python 기반 데이터 처리와 AI 기능 연동 경험을 바탕으로  
데이터를 읽고, 정리하고, 서비스에 연결하는 역량을 계속 확장하고 있습니다.

</section>
