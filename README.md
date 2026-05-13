
<style>
  .profile-wrap { max-width: 680px; padding: 2rem 0; font-family: var(--font-sans); color: var(--color-text-primary); }
  .avatar-row { display: flex; align-items: center; gap: 20px; margin-bottom: 1.5rem; }
  .avatar { width: 72px; height: 72px; border-radius: 50%; background: #EEEDFE; display: flex; align-items: center; justify-content: center; font-size: 26px; font-weight: 500; color: #3C3489; border: 0.5px solid #AFA9EC; flex-shrink: 0; }
  .name-block h1 { font-size: 22px; font-weight: 500; margin: 0 0 4px; }
  .name-block p { font-size: 14px; color: var(--color-text-secondary); margin: 0; }
  .badges { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 1.5rem; }
  .badge { font-size: 12px; padding: 4px 10px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-tertiary); color: var(--color-text-secondary); background: var(--color-background-secondary); }
  .bio { font-size: 15px; line-height: 1.7; color: var(--color-text-secondary); margin-bottom: 1.5rem; border-left: 2px solid #AFA9EC; padding-left: 1rem; }
  .section-title { font-size: 13px; font-weight: 500; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.06em; margin: 0 0 12px; }
  .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 10px; margin-bottom: 1.5rem; }
  .card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 14px 16px; }
  .card-icon { font-size: 20px; margin-bottom: 8px; color: #534AB7; }
  .card-label { font-size: 13px; font-weight: 500; margin-bottom: 4px; }
  .card-sub { font-size: 12px; color: var(--color-text-secondary); line-height: 1.5; }
  .stack-grid { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 1.5rem; }
  .tag { font-size: 13px; padding: 5px 12px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-tertiary); background: var(--color-background-secondary); color: var(--color-text-primary); }
  .links { display: flex; gap: 12px; flex-wrap: wrap; }
  .link-btn { display: inline-flex; align-items: center; gap: 6px; font-size: 13px; padding: 7px 14px; border-radius: var(--border-radius-md); border: 0.5px solid var(--color-border-secondary); color: var(--color-text-primary); text-decoration: none; background: transparent; cursor: pointer; }
  .link-btn:hover { background: var(--color-background-secondary); }
  hr { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 1.5rem 0; }
</style>

<div class="profile-wrap">
  <h2 class="sr-only">GitHub profile for Sheraz Ahmad — Senior Backend Engineer</h2>

  <div class="avatar-row">
    <div class="avatar">SA</div>
    <div class="name-block">
      <h1>Sheraz Ahmad</h1>
      <p>Senior Backend Engineer · Node.js & NestJS · AWS & Oracle Cloud</p>
    </div>
  </div>

  <p class="bio">
    I build the parts of software that users never see but always depend on — scalable APIs, cloud infrastructure, and systems that hold up under real load. I've spent the last few years working across the backend stack, from designing RESTful services with Django and Node.js to deploying on AWS and Oracle Cloud. I genuinely enjoy the problem-solving side of this work: making things faster, more reliable, and easier to maintain.
  </p>

  <hr>

  <p class="section-title">What I'm up to</p>
  <div class="cards">
    <div class="card">
      <div class="card-icon"><i class="ti ti-server" aria-hidden="true"></i></div>
      <div class="card-label">Building</div>
      <div class="card-sub">Scalable backend systems and production-grade web apps using modern cloud frameworks.</div>
    </div>
    <div class="card">
      <div class="card-icon"><i class="ti ti-users" aria-hidden="true"></i></div>
      <div class="card-label">Open to collaborate</div>
      <div class="card-sub">Backend-heavy projects, SaaS platforms, and open-source initiatives.</div>
    </div>
    <div class="card">
      <div class="card-icon"><i class="ti ti-target" aria-hidden="true"></i></div>
      <div class="card-label">Current focus</div>
      <div class="card-sub">Cloud-native development, DevOps automation, and high-performance architectures.</div>
    </div>
  </div>

  <hr>

  <p class="section-title">Tech stack</p>
  <div class="stack-grid">
    <span class="tag">Node.js</span>
    <span class="tag">NestJS</span>
    <span class="tag">Django & DRF</span>
    <span class="tag">TypeScript</span>
    <span class="tag">JavaScript</span>
    <span class="tag">React</span>
    <span class="tag">PostgreSQL</span>
    <span class="tag">MongoDB</span>
    <span class="tag">MySQL</span>
    <span class="tag">Firebase</span>
    <span class="tag">AWS</span>
    <span class="tag">Oracle Cloud</span>
    <span class="tag">Google Cloud</span>
    <span class="tag">Docker</span>
    <span class="tag">Git</span>
    <span class="tag">Tailwind CSS</span>
  </div>

  <hr>

  <p class="section-title">Get in touch</p>
  <div class="links">
    <a class="link-btn" href="https://www.linkedin.com/in/sheraz8814/" target="_blank">
      <i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn
    </a>
    <a class="link-btn" href="mailto:sheraz.ahmad8814@gmail.com">
      <i class="ti ti-mail" aria-hidden="true"></i> sheraz.ahmad8814@gmail.com
    </a>
    <a class="link-btn" href="https://github.com/sheraz02" target="_blank">
      <i class="ti ti-brand-github" aria-hidden="true"></i> GitHub
    </a>
  </div>
</div>
