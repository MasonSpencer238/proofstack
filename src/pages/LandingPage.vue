<template>
  <q-page class="proof-page">
    <div class="proof-bg proof-bg--one" aria-hidden="true"></div>
    <div class="proof-bg proof-bg--two" aria-hidden="true"></div>

    <!-- NAV -->
    <header class="proof-nav">
      <div class="proof-shell">
        <div class="proof-nav__row">
          <div class="proof-brand">
            <div class="proof-brand__mark proof-brand__mark--image">
              <img
                src="/images/logo-mark.svg"
                alt="ProofStack logo"
                class="proof-brand__mark-img"
              />
            </div>

            <div class="proof-brand__meta">
              <div class="proof-brand__name">ProofStack</div>
              <div class="proof-brand__sub">Proof of work. Instantly.</div>
            </div>
          </div>

          <div class="proof-nav__actions">
            <q-btn
              flat
              no-caps
              label="Features"
              class="proof-nav__link gt-sm"
              @click="scrollToSection('features')"
            />
            <q-btn
              flat
              no-caps
              label="How it works"
              class="proof-nav__link gt-sm"
              @click="scrollToSection('how-it-works')"
            />
            <q-btn
              flat
              no-caps
              label="Why ProofStack"
              class="proof-nav__link gt-sm"
              @click="scrollToSection('why-proofstack')"
            />
            <q-btn unelevated no-caps color="primary" label="Start free" class="proof-nav__cta" />
          </div>
        </div>
      </div>
    </header>

    <!-- HERO -->
    <section class="proof-hero">
      <div class="proof-shell">
        <div class="proof-hero__grid">
          <div class="proof-hero__content">
            <div class="proof-badge">
              Built for valeters, cleaners, contractors and property teams
            </div>

            <h1 class="proof-title">
              Stop chasing messages.
              <span>Send proof customers trust.</span>
            </h1>

            <p class="proof-subtitle">
              Turn everyday job photos into clean proof reports with timestamps, notes, location
              verification and shareable links your customers can trust.
            </p>

            <div class="proof-hero__actions">
              <q-btn
                unelevated
                no-caps
                color="primary"
                size="lg"
                label="Start free"
                class="proof-main-cta"
              />
              <q-btn
                flat
                no-caps
                size="lg"
                icon="visibility"
                label="See example report"
                class="proof-secondary-cta"
              />
            </div>

            <div class="proof-mini-points">
              <div class="proof-mini-point">
                <q-icon name="check_circle" size="18px" />
                <span>Look more professional instantly</span>
              </div>
              <div class="proof-mini-point">
                <q-icon name="check_circle" size="18px" />
                <span>Reduce customer disputes</span>
              </div>
              <div class="proof-mini-point">
                <q-icon name="check_circle" size="18px" />
                <span>Get proof out in seconds</span>
              </div>
            </div>
          </div>

          <div class="proof-hero__visual">
            <div class="proof-hero-card">
              <div class="proof-hero-card__top">
                <div class="proof-window-dots">
                  <span></span>
                  <span></span>
                  <span></span>
                </div>
                <div class="proof-window-title">Example Proof Report</div>
              </div>

              <div class="proof-hero-card__image-wrap">
                <img
                  src="/images/report-preview.png"
                  alt="ProofStack proof report preview"
                  class="proof-hero-card__image"
                />
              </div>
            </div>

            <div class="proof-floating proof-floating--left">
              <q-icon name="verified" size="18px" />
              <span>GPS & timestamp verified</span>
            </div>

            <div class="proof-floating proof-floating--right">
              <q-icon name="share" size="18px" />
              <span>Shareable client link</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- TRUST STRIP -->
    <section class="proof-trust">
      <div class="proof-shell">
        <div class="proof-trust__card">
          <div class="proof-trust__item">
            <div class="proof-trust__number">Before</div>
            <div class="proof-trust__label">Loose photos and message threads</div>
          </div>
          <div class="proof-trust__divider"></div>
          <div class="proof-trust__item">
            <div class="proof-trust__number">After</div>
            <div class="proof-trust__label">Professional reports customers trust</div>
          </div>
          <div class="proof-trust__divider"></div>
          <div class="proof-trust__item">
            <div class="proof-trust__number">Fast</div>
            <div class="proof-trust__label">Built for real jobs, not office admin</div>
          </div>
        </div>
      </div>
    </section>

    <!-- WHY IT MATTERS -->
    <section id="why-proofstack" class="proof-section proof-section--soft">
      <div class="proof-shell">
        <div class="proof-section-head">
          <div class="proof-kicker">Why it matters</div>
          <h2 class="proof-h2">The difference customers actually notice</h2>
          <p class="proof-p">
            Most service businesses already take photos. The real problem is how those photos are
            sent, presented and trusted.
          </p>
        </div>

        <div class="proof-compare">
          <div class="proof-compare-card proof-compare-card--bad">
            <div class="proof-compare-card__top">
              <q-icon name="sms" size="28px" />
              <h3>What you do now</h3>
            </div>

            <ul class="proof-list">
              <li>Send photos through WhatsApp or text</li>
              <li>Messages get buried or feel messy</li>
              <li>No clear timeline of what happened</li>
              <li>Customers can still question the job</li>
              <li>Your work looks less premium than it really is</li>
            </ul>
          </div>

          <div class="proof-compare-card proof-compare-card--good">
            <div class="proof-compare-card__top">
              <q-icon name="task_alt" size="28px" />
              <h3>With ProofStack</h3>
            </div>

            <ul class="proof-list">
              <li>Photos grouped neatly by job</li>
              <li>Time, notes and location all captured</li>
              <li>Clean reports generated instantly</li>
              <li>Professional share link for every customer</li>
              <li>Better trust, fewer disputes, stronger brand image</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- SHOWCASE -->
    <section class="proof-section proof-section--white">
      <div class="proof-shell">
        <div class="proof-showcase">
          <div class="proof-showcase__visual">
            <div class="proof-showcase-card">
              <img
                src="/images/report-preview.png"
                alt="ProofStack proof report"
                class="proof-showcase-card__image"
              />
            </div>
          </div>

          <div class="proof-showcase__content">
            <div class="proof-kicker">Product clarity</div>
            <h2 class="proof-h2">Proof that feels clear at a glance</h2>
            <p class="proof-p proof-p--left">
              Customers do not want a pile of loose photos. They want something that feels
              organised, trustworthy and easy to understand in seconds.
            </p>

            <div class="proof-showcase-points">
              <div class="proof-showcase-point">
                <div class="proof-showcase-point__icon">
                  <q-icon name="view_carousel" size="24px" />
                </div>
                <div>
                  <h3>Before and after, side by side</h3>
                  <p>
                    Show the difference clearly without making customers scroll through chat
                    history.
                  </p>
                </div>
              </div>

              <div class="proof-showcase-point">
                <div class="proof-showcase-point__icon">
                  <q-icon name="schedule" size="24px" />
                </div>
                <div>
                  <h3>Verified time and location</h3>
                  <p>Back your work up with evidence that feels credible and easy to trust.</p>
                </div>
              </div>

              <div class="proof-showcase-point">
                <div class="proof-showcase-point__icon">
                  <q-icon name="link" size="24px" />
                </div>
                <div>
                  <h3>Shareable proof link</h3>
                  <p>
                    Send one clean link instead of messy attachments, screenshots and message
                    threads.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- FEATURES -->
    <section id="features" class="proof-section proof-section--alt">
      <div class="proof-shell">
        <div class="proof-section-head proof-section-head--center">
          <div class="proof-kicker">Core features</div>
          <h2 class="proof-h2">Everything you need. Nothing that gets in the way.</h2>
          <p class="proof-p">Built to be fast enough for people actually out doing the job.</p>
        </div>

        <div class="proof-feature-grid">
          <div class="proof-feature-card">
            <div class="proof-feature-card__icon">
              <q-icon name="photo_camera" size="30px" />
            </div>
            <h3>Capture photos</h3>
            <p>Keep before, during and after images organised inside each job.</p>
          </div>

          <div class="proof-feature-card">
            <div class="proof-feature-card__icon">
              <q-icon name="schedule" size="30px" />
            </div>
            <h3>Automatic timestamps</h3>
            <p>Every image is locked to the time it was captured for better trust.</p>
          </div>

          <div class="proof-feature-card">
            <div class="proof-feature-card__icon">
              <q-icon name="place" size="30px" />
            </div>
            <h3>Location verified</h3>
            <p>Add GPS-backed proof to show where the work was actually completed.</p>
          </div>

          <div class="proof-feature-card">
            <div class="proof-feature-card__icon">
              <q-icon name="description" size="30px" />
            </div>
            <h3>Instant reports</h3>
            <p>Turn evidence into a polished customer-facing report in seconds.</p>
          </div>

          <div class="proof-feature-card">
            <div class="proof-feature-card__icon">
              <q-icon name="edit_note" size="30px" />
            </div>
            <h3>Add notes</h3>
            <p>Add quick context so customers understand exactly what was done.</p>
          </div>

          <div class="proof-feature-card">
            <div class="proof-feature-card__icon">
              <q-icon name="ios_share" size="30px" />
            </div>
            <h3>Share by link</h3>
            <p>Send proof fast without ugly attachments or long message threads.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- HOW -->
    <section id="how-it-works" class="proof-section proof-section--tint">
      <div class="proof-shell">
        <div class="proof-how">
          <div class="proof-how__left">
            <div class="proof-kicker">How it works</div>
            <h2 class="proof-h2">Simple enough to use in the real world</h2>
            <p class="proof-p proof-p--left">
              No bloated CRM. No complicated setup. Just a fast flow that turns everyday job photos
              into proof your customer can understand.
            </p>
          </div>

          <div class="proof-how__right">
            <div class="proof-step-card">
              <div class="proof-step-card__num">1</div>
              <div>
                <h3>Create the job</h3>
                <p>Set up a job in seconds with a name and optional notes.</p>
              </div>
            </div>

            <div class="proof-step-card">
              <div class="proof-step-card__num">2</div>
              <div>
                <h3>Capture the work</h3>
                <p>Take before and after photos directly inside the app.</p>
              </div>
            </div>

            <div class="proof-step-card">
              <div class="proof-step-card__num">3</div>
              <div>
                <h3>Generate proof</h3>
                <p>Build a professional report automatically from the evidence.</p>
              </div>
            </div>

            <div class="proof-step-card">
              <div class="proof-step-card__num">4</div>
              <div>
                <h3>Send it instantly</h3>
                <p>Share the proof link with your customer before they even ask.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- AUDIENCE -->
    <section class="proof-section proof-section--white proof-section--compact-bottom">
      <div class="proof-shell">
        <div class="proof-section-head proof-section-head--center">
          <div class="proof-kicker">Best fit</div>
          <h2 class="proof-h2">Built for teams whose work needs to be seen clearly</h2>
        </div>

        <div class="proof-audience">
          <div class="proof-chip">Car valeters</div>
          <div class="proof-chip">Detailers</div>
          <div class="proof-chip">Exterior cleaners</div>
          <div class="proof-chip">Pressure washers</div>
          <div class="proof-chip">Contractors</div>
          <div class="proof-chip">Drainage teams</div>
          <div class="proof-chip">Property managers</div>
          <div class="proof-chip">Maintenance teams</div>
        </div>
      </div>
    </section>

    <!-- FINAL CTA -->
    <section class="proof-final">
      <div class="proof-shell">
        <div class="proof-final__card">
          <div class="proof-kicker proof-kicker--light">Start now</div>
          <h2 class="proof-final__title">Your work looks great. Your proof should too.</h2>
          <p class="proof-final__text">
            Stop relying on chat threads and loose photos. Start sending proof that feels clear,
            credible and professional from job one.
          </p>

          <div class="proof-final__actions">
            <q-btn
              unelevated
              no-caps
              color="primary"
              size="lg"
              label="Start free"
              class="proof-main-cta"
            />
            <q-btn flat no-caps color="white" size="lg" icon="mail" label="Join waitlist" />
          </div>
        </div>
      </div>
    </section>
  </q-page>
</template>

<script setup lang="ts">
const scrollToSection = (id: string) => {
  const el = document.getElementById(id);
  if (!el) return;
  el.scrollIntoView({ behavior: 'smooth', block: 'start' });
};
</script>

<style scoped>
.proof-page {
  position: relative;
  overflow: hidden;
  background:
    radial-gradient(circle at top left, rgba(99, 102, 241, 0.1), transparent 28%),
    radial-gradient(circle at 85% 10%, rgba(59, 130, 246, 0.08), transparent 22%),
    linear-gradient(180deg, #0b1020 0%, #0f172a 21%, #f8fafc 21%, #f8fafc 100%);
  color: #0f172a;
}

.proof-bg {
  position: absolute;
  border-radius: 999px;
  filter: blur(80px);
  pointer-events: none;
  z-index: 0;
}

.proof-bg--one {
  width: 360px;
  height: 360px;
  background: rgba(79, 70, 229, 0.18);
  top: 60px;
  left: -120px;
}

.proof-bg--two {
  width: 340px;
  height: 340px;
  background: rgba(37, 99, 235, 0.14);
  top: 100px;
  right: -120px;
}

.proof-shell {
  position: relative;
  z-index: 1;
  width: min(1180px, calc(100% - 32px));
  margin: 0 auto;
}

.proof-nav {
  padding: 18px 0;
}

.proof-nav__row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
}

.proof-brand {
  display: flex;
  align-items: center;
  gap: 10px;
}

.proof-brand__mark {
  flex: 0 0 auto;
}

.proof-brand__mark--image {
  width: 46px;
  height: 46px;
  display: grid;
  place-items: center;
  background: transparent;
  box-shadow: none;
  border-radius: 0;
  padding: 0;
  overflow: visible;
}

.proof-brand__mark-img {
  display: block;
  width: 46px;
  height: 46px;
  object-fit: contain;
  transform: translateX(1px);
}

.proof-brand__meta {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.proof-brand__name {
  font-size: 18px;
  font-weight: 700;
  color: white;
  line-height: 1.05;
  letter-spacing: -0.02em;
}

.proof-brand__sub {
  font-size: 12px;
  color: rgba(255, 255, 255, 0.72);
  margin-top: 3px;
  line-height: 1.1;
}

.proof-nav__actions {
  display: flex;
  align-items: center;
  gap: 8px;
}

.proof-nav__link {
  color: rgba(255, 255, 255, 0.8);
  border-radius: 12px;
}

.proof-nav__cta {
  border-radius: 14px;
  padding-inline: 18px;
  font-weight: 700;
  box-shadow:
    0 12px 28px rgba(37, 99, 235, 0.28),
    inset 0 1px 0 rgba(255, 255, 255, 0.18);
}

.proof-hero {
  padding: 40px 0 74px;
}

.proof-hero__grid {
  display: grid;
  grid-template-columns: minmax(0, 0.95fr) minmax(0, 1.05fr);
  gap: 42px;
  align-items: center;
}

.proof-badge {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 10px 15px;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.08);
  border: 1px solid rgba(255, 255, 255, 0.14);
  color: rgba(255, 255, 255, 0.86);
  font-size: 13px;
  font-weight: 600;
  backdrop-filter: blur(16px);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.05);
}

.proof-title {
  margin: 18px 0 16px;
  font-size: clamp(42px, 6vw, 72px);
  line-height: 1.02;
  letter-spacing: -0.04em;
  font-weight: 800;
  color: white;
  max-width: 720px;
}

.proof-title span {
  display: block;
  margin-top: 8px;
  color: #93c5fd;
}

.proof-subtitle {
  max-width: 620px;
  font-size: 18px;
  line-height: 1.7;
  color: rgba(255, 255, 255, 0.84);
  margin: 0;
}

.proof-hero__actions {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-top: 28px;
  flex-wrap: wrap;
}

.proof-secondary-cta {
  color: rgba(255, 255, 255, 0.88);
  border-radius: 14px;
}

.proof-mini-points {
  display: flex;
  flex-wrap: wrap;
  gap: 18px;
  margin-top: 26px;
}

.proof-mini-point {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  color: rgba(255, 255, 255, 0.82);
  font-size: 14px;
}

.proof-mini-point .q-icon {
  color: #86efac;
}

.proof-hero__visual {
  position: relative;
  min-height: 520px;
}

.proof-hero-card {
  position: relative;
  border-radius: 28px;
  padding: 16px;
  background: rgba(255, 255, 255, 0.9);
  box-shadow:
    0 35px 90px rgba(2, 6, 23, 0.28),
    0 8px 24px rgba(15, 23, 42, 0.12);
  backdrop-filter: blur(14px);
  transform: perspective(1400px) rotateY(-8deg) rotateX(3deg);
  transform-origin: center;
  overflow: hidden;
}

.proof-hero-card__top {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 4px 6px 12px;
}

.proof-window-dots {
  display: flex;
  gap: 8px;
}

.proof-window-dots span {
  width: 10px;
  height: 10px;
  border-radius: 999px;
  background: #cbd5e1;
}

.proof-window-title {
  font-size: 13px;
  font-weight: 700;
  color: #475569;
}

.proof-hero-card__image-wrap {
  border-radius: 20px;
  overflow: hidden;
  background: #e2e8f0;
}

.proof-hero-card__image {
  display: block;
  width: 100%;
  height: auto;
}

.proof-floating {
  position: absolute;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 12px 14px;
  border-radius: 16px;
  background: rgba(15, 23, 42, 0.92);
  color: white;
  box-shadow: 0 20px 40px rgba(15, 23, 42, 0.25);
  font-size: 13px;
  font-weight: 600;
}

.proof-floating .q-icon {
  color: #93c5fd;
}

.proof-floating--left {
  left: -16px;
  bottom: 34px;
}

.proof-floating--right {
  right: -10px;
  top: 78px;
}

.proof-trust {
  margin-top: -8px;
  padding-bottom: 12px;
}

.proof-trust__card {
  display: grid;
  grid-template-columns: 1fr auto 1fr auto 1fr;
  align-items: center;
  gap: 18px;
  background: white;
  border: 1px solid rgba(15, 23, 42, 0.08);
  border-radius: 24px;
  padding: 22px 28px;
  box-shadow: 0 18px 40px rgba(15, 23, 42, 0.06);
}

.proof-trust__item {
  text-align: center;
}

.proof-trust__number {
  font-size: 18px;
  font-weight: 800;
  color: #111827;
}

.proof-trust__label,
.proof-p,
.proof-feature-card p,
.proof-step-card p,
.proof-showcase-point p {
  color: #5b6b82;
}

.proof-trust__label {
  margin-top: 6px;
  font-size: 14px;
}

.proof-trust__divider {
  width: 1px;
  height: 48px;
  background: #e2e8f0;
}

.proof-section {
  padding: 76px 0;
}

.proof-section--soft {
  background: #f8fafc;
}

.proof-section--white {
  background: #ffffff;
}

.proof-section--alt {
  background: linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
}

.proof-section--tint {
  background: linear-gradient(180deg, #f8fafc 0%, #f1f5f9 100%);
}

.proof-section--compact-bottom {
  padding-bottom: 56px;
}

.proof-section-head {
  max-width: 760px;
  margin-bottom: 34px;
}

.proof-section-head--center {
  margin-inline: auto;
  text-align: center;
}

.proof-kicker {
  display: inline-block;
  margin-bottom: 12px;
  font-size: 13px;
  font-weight: 800;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #4f46e5;
}

.proof-kicker--light {
  color: #93c5fd;
}

.proof-h2 {
  margin: 0;
  font-size: clamp(30px, 4vw, 52px);
  line-height: 1.08;
  letter-spacing: -0.035em;
  color: #0f172a;
}

.proof-p {
  margin-top: 16px;
  font-size: 17px;
  line-height: 1.75;
}

.proof-p--left {
  max-width: 560px;
}

.proof-compare {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
}

.proof-compare-card {
  border-radius: 26px;
  padding: 28px 28px 26px;
  border: 1px solid rgba(15, 23, 42, 0.08);
  background: white;
  box-shadow: 0 18px 40px rgba(15, 23, 42, 0.05);
}

.proof-compare-card--bad {
  background: linear-gradient(180deg, #fff7f7 0%, #ffffff 100%);
}

.proof-compare-card--good {
  background: linear-gradient(180deg, #f3fff7 0%, #ffffff 100%);
}

.proof-compare-card__top {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 18px;
}

.proof-compare-card__top h3 {
  margin: 0;
  font-size: 24px;
  font-weight: 800;
  color: #0f172a;
}

.proof-compare-card--bad .q-icon {
  color: #ef4444;
}

.proof-compare-card--good .q-icon {
  color: #16a34a;
}

.proof-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.proof-list li {
  position: relative;
  padding-left: 28px;
  margin-bottom: 14px;
  color: #334155;
  line-height: 1.65;
}

.proof-list li::before {
  content: '';
  position: absolute;
  left: 0;
  top: 10px;
  width: 10px;
  height: 10px;
  border-radius: 999px;
  background: #cbd5e1;
}

.proof-compare-card--bad .proof-list li::before {
  background: #f87171;
}

.proof-compare-card--good .proof-list li::before {
  background: #4ade80;
}

.proof-showcase {
  display: grid;
  grid-template-columns: minmax(0, 1.03fr) minmax(0, 0.97fr);
  gap: 34px;
  align-items: center;
}

.proof-showcase-card {
  border-radius: 28px;
  overflow: hidden;
  background:
    radial-gradient(circle at top left, rgba(99, 102, 241, 0.06), transparent 30%),
    linear-gradient(180deg, #eef2f7, #f8fafc);
  box-shadow:
    0 30px 70px rgba(15, 23, 42, 0.12),
    inset 0 1px 0 rgba(255, 255, 255, 0.65);
  border: 1px solid rgba(15, 23, 42, 0.08);
}

.proof-showcase-card__image {
  display: block;
  width: 100%;
  height: auto;
}

.proof-showcase-points {
  display: grid;
  gap: 18px;
  margin-top: 26px;
}

.proof-showcase-point {
  display: grid;
  grid-template-columns: auto 1fr;
  gap: 14px;
  align-items: start;
  padding: 18px;
  background: #f8fafc;
  border: 1px solid rgba(15, 23, 42, 0.06);
  border-radius: 20px;
}

.proof-showcase-point__icon {
  width: 46px;
  height: 46px;
  border-radius: 14px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #eef2ff, #dbeafe);
  color: #4f46e5;
}

.proof-showcase-point h3 {
  margin: 2px 0 6px;
  font-size: 20px;
  color: #0f172a;
}

.proof-showcase-point p {
  margin: 0;
  line-height: 1.7;
}

.proof-feature-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 22px;
  margin-top: 34px;
}

.proof-feature-card {
  background: white;
  border: 1px solid rgba(15, 23, 42, 0.08);
  border-radius: 24px;
  padding: 28px;
  box-shadow: 0 16px 34px rgba(15, 23, 42, 0.05);
  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.proof-feature-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 24px 44px rgba(15, 23, 42, 0.08);
}

.proof-feature-card__icon {
  width: 58px;
  height: 58px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 18px;
  background: linear-gradient(135deg, #eef2ff, #dbeafe);
  color: #4f46e5;
  margin-bottom: 18px;
}

.proof-feature-card h3 {
  margin: 0 0 10px;
  font-size: 23px;
  line-height: 1.15;
  color: #0f172a;
}

.proof-feature-card p {
  margin: 0;
  line-height: 1.7;
}

.proof-how {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  gap: 32px;
  align-items: start;
}

.proof-how__right {
  display: grid;
  gap: 16px;
}

.proof-step-card {
  display: grid;
  grid-template-columns: auto 1fr;
  gap: 16px;
  align-items: start;
  padding: 20px;
  border-radius: 20px;
  background: white;
  border: 1px solid rgba(15, 23, 42, 0.08);
  box-shadow: 0 14px 30px rgba(15, 23, 42, 0.04);
}

.proof-step-card__num {
  width: 42px;
  height: 42px;
  border-radius: 14px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #6366f1, #2563eb);
  color: white;
  font-weight: 800;
  box-shadow: 0 10px 24px rgba(37, 99, 235, 0.22);
}

.proof-step-card h3 {
  margin: 2px 0 6px;
  font-size: 20px;
  color: #0f172a;
}

.proof-step-card p {
  margin: 0;
  line-height: 1.7;
}

.proof-audience {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  justify-content: center;
  margin-top: 18px;
}

.proof-main-cta {
  border-radius: 14px;
  padding-inline: 18px;
  font-weight: 700;
  box-shadow:
    0 12px 28px rgba(37, 99, 235, 0.28),
    inset 0 1px 0 rgba(255, 255, 255, 0.18);
  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.proof-main-cta:hover {
  transform: translateY(-1px);
  box-shadow:
    0 16px 34px rgba(37, 99, 235, 0.34),
    inset 0 1px 0 rgba(255, 255, 255, 0.22);
}

.proof-chip {
  padding: 13px 18px;
  border-radius: 999px;
  background: linear-gradient(180deg, #ffffff, #f8fafc);
  border: 1px solid rgba(15, 23, 42, 0.08);
  box-shadow: 0 12px 26px rgba(15, 23, 42, 0.05);
  color: #243247;
  font-weight: 700;
  letter-spacing: -0.01em;
}

.proof-final {
  padding: 8px 0 88px;
}

.proof-final__card {
  border-radius: 32px;
  padding: 54px 38px;
  background:
    radial-gradient(circle at top right, rgba(59, 130, 246, 0.2), transparent 30%),
    linear-gradient(135deg, #0f172a, #111827 55%, #172554);
  color: white;
  box-shadow: 0 30px 70px rgba(15, 23, 42, 0.22);
  text-align: center;
}

.proof-final__title {
  margin: 0;
  font-size: clamp(32px, 4vw, 52px);
  line-height: 1.08;
  letter-spacing: -0.03em;
}

.proof-final__text {
  max-width: 760px;
  margin: 16px auto 0;
  font-size: 18px;
  line-height: 1.8;
  color: rgba(255, 255, 255, 0.74);
}

.proof-final__actions {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 12px;
  margin-top: 28px;
  flex-wrap: wrap;
}

@media (max-width: 1180px) {
  .proof-hero__grid,
  .proof-how,
  .proof-showcase {
    grid-template-columns: 1fr;
  }

  .proof-hero__visual {
    min-height: auto;
  }

  .proof-hero-card {
    transform: none;
  }

  .proof-floating--left {
    left: 8px;
    bottom: 18px;
  }

  .proof-floating--right {
    right: 8px;
    top: 18px;
  }
}

@media (max-width: 900px) {
  .proof-trust__card,
  .proof-compare,
  .proof-feature-grid {
    grid-template-columns: 1fr;
  }

  .proof-trust__card {
    grid-template-columns: 1fr;
  }

  .proof-trust__divider {
    display: none;
  }
}

@media (max-width: 640px) {
  .proof-shell {
    width: min(100% - 20px, 1180px);
  }

  .proof-nav__link {
    display: none;
  }

  .proof-title {
    font-size: 38px;
  }

  .proof-subtitle {
    font-size: 16px;
  }

  .proof-section {
    padding: 74px 0;
  }

  .proof-final {
    padding-bottom: 80px;
  }

  .proof-compare-card,
  .proof-feature-card,
  .proof-final__card,
  .proof-showcase-point {
    padding: 22px;
  }

  .proof-floating {
    position: static;
    margin-top: 12px;
  }

  .proof-hero__visual {
    display: flex;
    flex-direction: column;
  }

  .proof-mini-points {
    gap: 12px;
  }
}
</style>
