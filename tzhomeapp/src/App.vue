<!-- 파일: tzhome/tzhomeapp/src/App.vue -->
<template>
  <div class="site">
    <header class="topbar">
      <a class="brand" href="#home">
        <span class="brand-mark">T</span>
        <span>TAZOCODE</span>
      </a>

      <nav class="nav">
        <a href="#apps">Apps</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section id="home" class="hero section">
        <div>
          <p class="eyebrow">Personal App Studio</p>
          <h1>실용적인 앱 서비스를 만드는<br />타조코드입니다.</h1>
          <p class="hero-text">
            TAZOCODE는 웹 서비스와 모바일 앱을 직접 기획, 개발, 운영하는
            1인 개발 브랜드입니다.
          </p>

          <div class="hero-actions">
            <a class="primary-button" href="#apps">앱 보기</a>
            <a class="secondary-button" href="/privacy.html">개인정보처리방침</a>
          </div>
        </div>

        <div class="hero-card">
          <div class="card-row">
            <span>Web</span>
            <strong>Vue / Node.js</strong>
          </div>
          <div class="card-row">
            <span>Mobile</span>
            <strong>Ionic / Capacitor</strong>
          </div>
          <div class="card-row">
            <span>Server</span>
            <strong>Ubuntu / Nginx</strong>
          </div>
        </div>
      </section>

      <section id="apps" class="section">
        <div class="section-head">
          <p class="eyebrow">Apps</p>
          <h2>운영 및 준비 중인 서비스</h2>
          <p>간단하고 반복 사용성이 높은 앱을 중심으로 개발합니다.</p>
        </div>

        <div class="app-grid">
          <article class="app-card">
            <div class="app-icon">W</div>
            <h3>체중 기록 - TZ Weight</h3>
            <p>빠르게 체중을 기록하고 변화 흐름을 확인하는 체중 관리 앱입니다.</p>
            <span class="status">준비 중</span>
          </article>

          <article class="app-card">
            <div class="app-icon">C</div>
            <h3>TZ Chat</h3>
            <p>친구 찾기와 채팅을 중심으로 한 커뮤니케이션 서비스입니다.</p>
            <span class="status">준비 중</span>
          </article>

          <article class="app-card">
            <div class="app-icon">+</div>
            <h3>New Apps</h3>
            <p>생활에 필요한 작은 기능 앱들을 순차적으로 추가할 예정입니다.</p>
            <span class="status">계획 중</span>
          </article>
        </div>
      </section>

      <section id="about" class="section split-section">
        <div>
          <p class="eyebrow">About</p>
          <h2>일상을 개발합니다. </h2>
        </div>
        <p>
          타조코드는 1인 개발 구조에 맞춰 단순하고 유지보수 가능한 서비스를 지향합니다.
          웹 홈페이지, 모바일 앱, 서버 운영까지 직접 관리하며 안정적인 서비스 기반을 만들어갑니다.
        </p>
      </section>

      <section id="contact" class="section contact-section">
        <p class="eyebrow">Contact</p>
        <h2>문의</h2>
        <p>서비스 관련 문의는 아래 이메일로 연락해 주세요.</p>
        <a class="email-link" href="mailto:tazocode@gmail.com">tazocode@gmail.com</a>
      </section>
    </main>

    <footer class="footer">
      <div>
        <strong>TAZOCODE</strong>
        <p>© 2026 TAZOCODE. All rights reserved.</p>
      </div>

      <div class="footer-links">
        <a href="/privacy.html">Privacy</a>
        <a href="/terms.html">Terms</a>
        <a href="/app-ads.txt">app-ads.txt</a>
        <a href="/ads.txt">ads.txt</a>
      </div>
    </footer>
  </div>
</template>