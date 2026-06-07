<!-- 파일: tzhome/tzhomeapp/src/App.vue -->
<template>
  <div class="site">
    <header class="topbar">
      <a class="brand" href="#home">
        <span class="brand-mark">
          <img src="/tazocode-logo.jpeg" alt="TAZOCODE 로고" />
        </span>
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

          <h1>TAZOCODE</h1>

          <h2>일상을 개발합니다.</h2>

          <p class="hero-text">
            TAZOCODE는 웹 서비스, 모바일 앱, 서버 운영까지<br />
            관리하는 개발 브랜드입니다.
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
          <p>생활 중심형 앱을 중심으로 개발하고 있습니다.</p>
        </div>

        <div class="app-grid">
          <article class="app-card">
            <div class="app-icon">W</div>
            <h3>TZ Weight</h3>
            <p>빠르게 체중을 기록하고 변화 흐름을 확인하는 체중 관리 앱입니다.</p>
            <span class="status">운영 중</span>
          </article>

          <article class="app-card">
            <div class="app-icon">C</div>
            <h3>TZ Chat</h3>
            <p>친구 찾기와 채팅을 중심으로 한 커뮤니케이션 서비스입니다.</p>
            <span class="status">운영 준비 중</span>
          </article>

          <article class="app-card">
            <div class="app-icon">+</div>
            <h3>New Apps</h3>
            <p>생활에 필요한 작은 기능 앱들을 순차적으로 추가할 예정입니다.</p>
            <span class="status">계획 중</span>
          </article>
        </div>
      </section>

      <section id="about" class="section about-section">
        <div class="section-head">
          <p class="eyebrow">About</p>
          <h2>개발 과정과 일상을 공유합니다.</h2>
          <p>
            앱을 만들고, 사용하고, 새로운 서비스를 실험합니다.<br />
            TAZOCODE의 과정은 유튜브, 인스타그램, 쓰레드에서 <br/>
            함께 볼 수 있습니다.
          </p>
        </div>

        <div class="social-grid">
          <a
            class="social-card youtube-card"
            href="https://www.youtube.com/@tazocode"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="TAZOCODE YouTube"
          >
            <span class="social-icon" aria-hidden="true">
              <img src="/youtube-logo.png" alt="" />
            </span>
            <div>
              <strong>YouTube</strong>
              <p>앱 개발과 일상 기록</p>
            </div>
          </a>

          <a
            class="social-card instagram-card"
            href="https://www.instagram.com/tazocode"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="TAZOCODE Instagram"
          >
            <span class="social-icon" aria-hidden="true">
              <img src="/Instagram-logo.png" alt="" />
            </span>
            <div>
              <strong>Instagram</strong>
              <p>이미지와 짧은 기록</p>
            </div>
          </a>

          <a
            class="social-card threads-card"
            href="https://www.threads.com/@tazocode"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="TAZOCODE Threads"
          >
            <span class="social-icon" aria-hidden="true">
              <img src="/threads-logo.avif" alt="" />
            </span>
            <div>
              <strong>Threads</strong>
              <p>생각과 과정 공유</p>
            </div>
          </a>
        </div>
      </section>

      <section id="contact" class="section contact-section">
        <p class="eyebrow">Contact</p>
        <h2>문의</h2>
        <p>서비스 관련 문의는 아래 이메일로 연락해 주세요.</p>
        <a class="email-link" href="mailto:tazocode@gmail.com">
          tazocode@gmail.com
        </a>
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

<style scoped>
.site {
  width: 100%;
  min-height: 100vh;
  padding: 16px 12px;
  color: #111827;
  background:
    radial-gradient(circle at top left, rgba(255, 218, 150, 0.26), transparent 34%),
    linear-gradient(180deg, #fffaf1 0%, #f8fafc 52%, #f3f4f6 100%);
}

.topbar {
  position: sticky;
  top: 0;
  z-index: 10;

  display: flex;
  flex-direction: column;
  gap: 10px;

  padding: 12px 14px;
  margin-bottom: 26px;

  background: rgba(255, 255, 255, 0.86);
  backdrop-filter: blur(14px);
  border-bottom: 1px solid rgba(17, 24, 39, 0.08);
}

.brand {
  display: inline-flex;
  align-items: center;
  gap: 10px;

  color: #111827;
  font-size: 15px;
  font-weight: 900;
  text-decoration: none;
}

.brand-mark {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;

  width: 34px;
  height: 34px;

  background: #111827;
  border-radius: 12px;
}

.brand-mark img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.nav {
  display: flex;
  justify-content: space-between;
  gap: 14px;
}

.nav a {
  color: #4b5563;
  font-size: 13px;
  font-weight: 800;
  text-decoration: none;
}

.section {
  padding: 24px 0 56px;
}

.hero {
  display: grid;
  gap: 26px;
}

.eyebrow {
  margin: 0 0 12px;

  color: #92400e;
  font-size: 12px;
  font-weight: 900;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

h1,
h2,
h3,
p {
  margin-top: 0;
}

h1 {
  margin-bottom: 12px;

  color: #111827;
  font-size: clamp(38px, 11vw, 56px);
  line-height: 1.02;
  letter-spacing: -0.07em;
}

h2 {
  margin-bottom: 18px;

  color: #111827;
  font-size: clamp(26px, 7vw, 38px);
  line-height: 1.18;
  letter-spacing: -0.05em;
}

h3 {
  margin-bottom: 14px;

  color: #111827;
  font-size: 21px;
  line-height: 1.3;
  letter-spacing: -0.03em;
}

.hero-text,
.section-head p,
.app-card p,
.social-card p,
.contact-section p,
.footer p {
  color: #4b5563;
  font-size: 15px;
  font-weight: 600;
  line-height: 1.85;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 28px;
}

.primary-button,
.secondary-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  min-height: 46px;
  padding: 0 18px;

  font-size: 14px;
  font-weight: 900;
  text-decoration: none;

  border-radius: 999px;
}

.primary-button {
  color: #ffffff;
  background: #111827;
}

.secondary-button {
  color: #111827;
  background: #ffffff;
  border: 1px solid #e5e7eb;
}

.hero-card,
.app-card,
.social-card,
.contact-section {
  background: rgba(255, 255, 255, 0.92);
  border: 1px solid #e5e7eb;
  border-radius: 24px;
  box-shadow: 0 20px 45px rgba(15, 23, 42, 0.08);
}

.hero-card {
  padding: 24px 22px;
}

.card-row {
  display: flex;
  justify-content: space-between;
  gap: 16px;

  padding: 15px 0;

  border-bottom: 1px solid #eef2f7;
}

.card-row:first-child {
  padding-top: 0;
}

.card-row:last-child {
  padding-bottom: 0;
  border-bottom: 0;
}

.card-row span {
  color: #6b7280;
  font-weight: 800;
}

.card-row strong {
  color: #111827;
  font-weight: 900;
  text-align: right;
}

.section-head {
  margin-bottom: 28px;
}

.app-grid,
.social-grid {
  display: grid;
  gap: 18px;
}

.app-card {
  padding: 24px;
}

.app-icon,
.social-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;

  width: 46px;
  height: 46px;

  color: #ffffff;
  font-size: 15px;
  font-weight: 900;

  background: #111827;
  border-radius: 14px;
}

.app-icon {
  margin-bottom: 20px;
}

.social-icon {
  background: transparent;
}

.social-icon img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.status {
  display: inline-flex;
  align-items: center;

  margin-top: 18px;
  padding: 7px 11px;

  color: #92400e;
  font-size: 12px;
  font-weight: 900;

  background: #fef3c7;
  border-radius: 999px;
}

.about-section {
  padding-bottom: 50px;
}

.social-card {
  display: flex;
  align-items: center;
  gap: 16px;

  padding: 20px;

  color: inherit;
  text-decoration: none;
  transition:
    border-color 0.2s ease,
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.social-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 24px 52px rgba(15, 23, 42, 0.12);
}

.youtube-card:hover {
  border-color: #ff0033;
}

.instagram-card:hover {
  border-color: #dd2a7b;
}

.threads-card:hover {
  border-color: #000000;
}

.social-card strong {
  display: block;
  margin-bottom: 4px;

  color: #111827;
  font-size: 17px;
  font-weight: 900;
}

.social-card p {
  margin: 0;
  font-size: 13px;
  line-height: 1.5;
}

.contact-section {
  padding: 34px 22px;
  text-align: center;
}

.contact-section .eyebrow {
  color: #4b5563;
}

.email-link {
  display: inline-block;
  margin-top: 10px;

  color: #111827;
  font-size: 16px;
  font-weight: 900;
  text-decoration-thickness: 2px;
}

.footer {
  display: grid;
  gap: 18px;

  padding: 28px 0 4px;

  border-top: 1px solid #e5e7eb;
}

.footer strong {
  color: #111827;
  font-size: 15px;
}

.footer p {
  margin: 8px 0 0;
  font-size: 13px;
  line-height: 1.5;
}

.footer-links {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
}

.footer-links a {
  color: #4b5563;
  font-size: 13px;
  font-weight: 900;
  text-decoration: none;
}

@media (min-width: 768px) {
  .site {
    max-width: 1080px;
    margin: 0 auto;
    padding: 24px;
  }

  .topbar {
    flex-direction: row;
    align-items: center;
    justify-content: space-between;

    padding: 14px 18px;
    border-radius: 20px;
    border: 1px solid rgba(17, 24, 39, 0.08);
  }

  .nav {
    justify-content: flex-end;
    gap: 28px;
  }

  .hero {
    grid-template-columns: minmax(0, 1.2fr) minmax(280px, 0.8fr);
    align-items: center;
  }

  .section {
    padding: 48px 0 80px;
  }

  .app-grid {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .social-grid {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .social-card {
    flex-direction: column;
    align-items: flex-start;
  }

  .footer {
    grid-template-columns: 1fr auto;
    align-items: center;
  }
}
</style>