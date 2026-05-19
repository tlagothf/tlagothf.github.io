---
layout: single
title: "Data & AI Portfolio"
permalink: /data-portfolio/
author_profile: false
---

<style>
/* 기존 포트폴리오 헤더/네비/자동 제목 숨김 */
.masthead,
.greedy-nav,
.author__avatar,
.author__content,
.author__urls-wrapper,
.page__title {
  display: none !important;
}

/* 기존 포트폴리오의 page 카드 스타일 제거 */
.page {
  max-width: none !important;
  margin: 0 !important;
  padding: 0 !important;
  background: transparent !important;
  border-radius: 0 !important;
  box-shadow: none !important;
}

/* Minimal Mistakes 내부 여백 초기화 */
.page__inner-wrap,
.page__content {
  max-width: none !important;
  margin: 0 !important;
  padding: 0 !important;
}

/* 전체 배경 */
body {
  background: #f5f7fb;
}

/* 이 숨김 포트폴리오 전용 카드 */
.data-page {
  max-width: 980px;
  margin: 3rem auto;
  background: #ffffff;
  border-radius: 22px;
  padding: 3rem;
  box-shadow: 0 18px 45px rgba(15, 23, 42, 0.1);
}

/* 히어로 영역 */
.data-hero {
  display: flex;
  align-items: center;
  gap: 2rem;
  padding-bottom: 2.5rem;
  border-bottom: 1px solid #e5e7eb;
}

.data-profile-img {
  width: 140px;
  height: 140px;
  border-radius: 999px;
  object-fit: cover;
  box-shadow: 0 10px 25px rgba(15, 23, 42, 0.16);
}

.data-hero-text {
  max-width: 620px;
}

.data-hero h1 {
  margin: 0 0 .8rem;
  font-size: 2.4rem;
  line-height: 1.25;
  color: #111827;
}

.data-hero p {
  margin: 0;
  color: #4b5563;
  line-height: 1.8;
}

.data-tagline {
  margin-top: .9rem !important;
  font-weight: 700;
  color: #0b1120 !important;
}

.section-block {
  margin-top: 3rem;
}

.section-block h2 {
  margin-top: 0;
  margin-bottom: 1.2rem;
  font-size: 1.45rem;
  color: #0b1120;
}

.section-block p {
  line-height: 1.8;
  color: #374151;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 1.1rem;
  margin-top: 1.2rem;
}

.info-card {
  background: #f9fafb;
  border-radius: 16px;
  padding: 1.35rem 1.4rem;
  box-shadow: 0 8px 20px rgba(15, 23, 42, 0.06);
}

.info-card h3 {
  margin: 0 0 .55rem;
  font-size: 1rem;
  color: #111827;
}

.info-card p {
  margin: 0;
  font-size: .9rem;
  line-height: 1.7;
  color: #4b5563;
}

.badge-wrap {
  margin-top: 1rem;
}

.badge {
  display: inline-block;
  padding: .38rem .75rem;
  margin: .25rem;
  border-radius: 999px;
  background: #eef2ff;
  color: #1e3a8a;
  font-size: .85rem;
  font-weight: 700;
}

.project-box {
  margin-top: 1.4rem;
  padding: 1.5rem 1.6rem;
  border-radius: 16px;
  background: #ffffff;
  border-left: 5px solid #0b1120;
  box-shadow: 0 10px 24px rgba(15, 23, 42, 0.07);
}

.project-box h3 {
  margin-top: 0;
  margin-bottom: .8rem;
  font-size: 1.15rem;
  color: #111827;
}

.project-box p {
  margin-bottom: .8rem;
  line-height: 1.75;
  color: #374151;
}

.project-box ul {
  margin-top: .6rem;
  margin-bottom: 1rem;
}

.project-box li {
  line-height: 1.75;
  color: #374151;
}

.contact-box {
  margin-top: 3rem;
  padding: 1.5rem;
  border-radius: 16px;
  background: #0b1120;
  color: #ffffff;
}

.contact-box strong {
  color: #ffffff;
}

.contact-box a {
  color: #dbeafe;
  font-weight: 700;
}

@media (max-width: 720px) {
  .data-page {
    margin: 1.5rem;
    padding: 2rem 1.5rem;
  }

  .data-hero {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .data-profile-img {
    width: 120px;
    height: 120px;
  }

  .data-hero h1 {
    font-size: 2rem;
  }
}
</style>

<div class="data-hero">
  <img src="/assets/images/profile.jpg" alt="심해솔 프로필 사진" class="data-profile-img">

  <div class="data-hero-text">
    <h1>Data & AI Portfolio</h1>

    <p>
      안녕하세요. 저는 <strong>Java 백엔드 개발 경험</strong>을 바탕으로
      Python 데이터 처리와 AI 기능 연동까지 함께 다루는 개발자 <strong>심해솔</strong>입니다.
    </p>

    <p class="data-tagline">
      데이터를 이해하고, 서비스 기능으로 연결하는 개발자를 지향합니다.
    </p>
  </div>
</div>

<section class="section-block">
  <h2>About</h2>

  <p>
    백엔드 개발을 하면서 단순히 기능을 구현하는 것뿐 아니라,
    데이터가 어떤 구조로 저장되고, 어떤 흐름으로 활용되며,
    서비스 개선에 어떻게 연결될 수 있는지에 관심을 갖게 되었습니다.
  </p>

  <p>
    Java/JSP/MyBatis 기반 시스템 개발 경험과 함께,
    Python을 활용한 데이터 수집, 전처리, 텍스트 분석, AI 연동 경험을 쌓아왔습니다.
  </p>

  <p>
    아직 데이터 분석 실무를 깊게 수행한 단계는 아니지만,
    실제 프로젝트를 통해 <strong>데이터 수집 → 전처리 → 분석 → 서비스 기능화</strong>의 흐름을 경험했고,
    앞으로는 데이터 분석과 AI 서비스 개발 역량을 더 깊게 확장하고자 합니다.
  </p>
</section>

<section class="section-block">
  <h2>Core Strengths</h2>

  <div class="card-grid">

    <div class="info-card">
      <h3>서비스 흐름 이해</h3>
      <p>
        기능 구현에서 끝나지 않고, 사용자가 어떤 흐름으로 서비스를 이용하는지 함께 고민합니다.
      </p>
    </div>

    <div class="info-card">
      <h3>데이터 처리 경험</h3>
      <p>
        Python, Pandas, Selenium, MySQL 등을 활용해 데이터를 수집하고 분석 가능한 형태로 정리한 경험이 있습니다.
      </p>
    </div>

    <div class="info-card">
      <h3>AI 기능 연동</h3>
      <p>
        LangChain, OpenAI API, Flask를 활용해 Java 시스템과 AI 기능을 연결한 경험이 있습니다.
      </p>
    </div>

    <div class="info-card">
      <h3>문제 해결 태도</h3>
      <p>
        오류가 발생하면 로그와 데이터 흐름을 추적해 원인을 찾고, 실제 동작까지 개선하는 편입니다.
      </p>
    </div>

  </div>
</section>

<section class="section-block">
  <h2>Skills</h2>

  <div class="badge-wrap">
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
  </div>
</section>

<section class="section-block">
  <h2>Project Experience</h2>

  <div class="project-box">
    <h3>사용자 맞춤형 영화 추천 프로그램</h3>

    <p>
      Python을 활용해 영화 데이터를 수집하고,
      텍스트 전처리와 임베딩 기반 유사도 분석을 통해 추천 로직을 구현했습니다.
    </p>

    <ul>
      <li>Selenium 기반 영화 데이터 수집</li>
      <li>JSON 데이터 파싱</li>
      <li>Kiwi 기반 형태소 분석</li>
      <li>불용어 처리 및 텍스트 정제</li>
      <li>FastText 기반 임베딩 처리</li>
      <li>유사도 계산 기반 추천 로직 구현</li>
      <li>MySQL DB 설계 및 연동</li>
    </ul>

    <p>
      이 프로젝트를 통해 데이터를 단순히 수집하는 것보다,
      분석 가능한 형태로 정리하고 서비스 기능으로 연결하는 과정이 중요하다는 것을 경험했습니다.
    </p>
  </div>

  <div class="project-box">
    <h3>AI 기반 문제은행 자동 생성 기능</h3>

    <p>
      LMS 시스템에서 교과 내용을 입력하면
      GPT 기반으로 객관식/주관식 문제를 자동 생성하는 기능을 개발했습니다.
    </p>

    <ul>
      <li>LangChain PromptTemplate 구성</li>
      <li>OutputParser 기반 JSON 응답 가공</li>
      <li>Flask API 서버 구성</li>
      <li>Java 시스템과 Python AI 모듈 연동</li>
      <li>생성 결과를 문제은행 DB에 저장</li>
    </ul>

    <p>
      이 경험을 통해 AI 응답을 실제 시스템에서 사용할 수 있는
      구조화된 데이터로 변환하는 과정을 배웠습니다.
    </p>
  </div>

  <div class="project-box">
    <h3>GPT 기반 챗봇 기능 개발</h3>

    <p>
      사용자가 질문을 입력하면 GPT 기반 챗봇이 응답하는 기능을 개발했습니다.
    </p>

    <ul>
      <li>LangChain 기반 대화 흐름 구성</li>
      <li>GPT API 연동</li>
      <li>Flask 서버와 Java/JSP 화면 연동</li>
      <li>사용자 질의 로그 저장</li>
      <li>응답 포맷 및 통신 오류 디버깅</li>
    </ul>

    <p>
      단순 챗봇 구현을 넘어,
      사용자 입력과 응답 데이터를 안정적으로 처리하는 구조를 고민한 경험입니다.
    </p>
  </div>

  <div class="project-box">
    <h3>백엔드 성능 개선 경험</h3>

    <p>
      전기차 서비스 백엔드에서 PostgreSQL 기반 조회 성능 개선을 경험했습니다.
    </p>

    <ul>
      <li>느린 쿼리 분석</li>
      <li>인덱스 추가</li>
      <li>SSE 및 조회 API 성능 개선</li>
      <li>기존 API 구조 리팩터링</li>
    </ul>

    <p>
      이 경험을 통해 데이터베이스 구조와 쿼리 설계가
      서비스 품질에 직접적인 영향을 준다는 점을 체감했습니다.
    </p>
  </div>
</section>

<section class="section-block">
  <h2>Direction</h2>

  <p>
    저는 앞으로 <strong>데이터를 이해하는 백엔드 개발자</strong>,
    그리고 <strong>서비스 데이터를 분석해 개선 방향을 제안할 수 있는 개발자</strong>로 성장하고 싶습니다.
  </p>

  <p>
    기능을 만드는 것에서 멈추지 않고,
    데이터가 어떤 의미를 가지는지 해석하고
    그 결과를 더 나은 서비스 구조로 연결하는 개발자가 되는 것이 목표입니다.
  </p>
</section>

<div class="contact-box">
  <strong>Contact</strong><br>
  Email: <a href="mailto:sunsol33@naver.com">sunsol33@naver.com</a><br>
  GitHub: <a href="https://github.com/tlagothf">github.com/tlagothf</a>
</div>
