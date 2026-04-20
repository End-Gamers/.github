
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#080810;font-family:'IBM Plex Mono',monospace}
.wrap{background:#080810;min-height:100vh;padding:32px 24px;color:#f0ede6}
.header{border-bottom:1px solid #1e1e3a;padding-bottom:28px;margin-bottom:28px;display:flex;align-items:flex-start;gap:24px}
.avatar{width:80px;height:80px;border-radius:50%;background:#111128;border:2px solid #ffbc0040;flex-shrink:0;display:flex;align-items:center;justify-content:center;position:relative}
.avatar-inner{width:36px;height:36px;position:relative}
.avatar svg{width:36px;height:36px}
.header-text{flex:1}
.team-name{font-family:'Noto Serif KR',serif;font-size:22px;font-weight:700;color:#f0ede6;letter-spacing:2px;margin-bottom:4px}
.project-name{font-family:'IBM Plex Mono',monospace;font-size:11px;color:#ffbc00;letter-spacing:3px;margin-bottom:10px}
.desc{font-family:'Noto Serif KR',serif;font-size:13px;color:#7a7670;line-height:1.8;font-weight:300}
.badges{display:flex;flex-wrap:wrap;gap:6px;margin-top:12px}
.badge{font-family:'IBM Plex Mono',monospace;font-size:10px;padding:3px 10px;border-radius:2px;letter-spacing:1px;border:1px solid}
.badge-gold{color:#b8860b;border-color:#ffbc0040;background:#ffbc000d}
.badge-blue{color:#4080c0;border-color:#4080c040;background:#4080c00d}
.badge-gray{color:#555570;border-color:#33334a;background:#11111e}
.section{margin-bottom:24px}
.section-label{font-family:'IBM Plex Mono',monospace;font-size:10px;color:#3a3a5a;letter-spacing:3px;text-transform:uppercase;margin-bottom:12px;display:flex;align-items:center;gap:10px}
.section-label::after{content:'';flex:1;height:1px;background:#1a1a2e}
.stat-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:#1a1a2e;margin-bottom:1px}
.stat-card{background:#0d0d18;padding:16px 14px}
.stat-num{font-family:'IBM Plex Mono',monospace;font-size:22px;font-weight:400;color:#f0ede6;margin-bottom:3px}
.stat-num.gold{color:#ffbc00}
.stat-num.red{color:#ff3b30}
.stat-label{font-family:'IBM Plex Mono',monospace;font-size:10px;color:#3a3a5a;letter-spacing:1px}
.stack-list{display:flex;flex-direction:column;gap:1px;background:#1a1a2e}
.stack-item{background:#0d0d18;padding:12px 16px;display:flex;align-items:center;justify-content:space-between}
.stack-name{font-family:'IBM Plex Mono',monospace;font-size:12px;color:#c8c4bc}
.stack-bar-wrap{width:160px;height:2px;background:#1a1a2e}
.stack-bar{height:2px}
.stack-role{font-family:'IBM Plex Mono',monospace;font-size:10px;color:#3a3a5a;min-width:80px;text-align:right}
.timeline{display:flex;flex-direction:column;gap:1px;background:#1a1a2e}
.tl-item{background:#0d0d18;padding:14px 16px;display:grid;grid-template-columns:80px 1fr;gap:16px}
.tl-week{font-family:'IBM Plex Mono',monospace;font-size:10px;color:#3a3a5a}
.tl-text{font-family:'IBM Plex Mono',monospace;font-size:11px;color:#7a7670}
.tl-text.active{color:#ffbc00}
.tl-text.done{color:#2a6a3a}
.team-grid{display:grid;grid-template-columns:1fr 1fr;gap:1px;background:#1a1a2e}
.team-card{background:#0d0d18;padding:16px}
.team-role{font-family:'IBM Plex Mono',monospace;font-size:10px;color:#ffbc00;letter-spacing:2px;margin-bottom:6px}
.team-skills{display:flex;flex-wrap:wrap;gap:4px;margin-top:8px}
.skill-tag{font-family:'IBM Plex Mono',monospace;font-size:10px;padding:2px 8px;background:#111128;border:1px solid #1e1e3a;color:#555570;border-radius:2px}
.footer{border-top:1px solid #1a1a2e;padding-top:16px;margin-top:8px;display:flex;justify-content:space-between;align-items:center}
.footer-left{font-family:'IBM Plex Mono',monospace;font-size:10px;color:#2a2a3a}
.footer-right{font-family:'IBM Plex Mono',monospace;font-size:10px;color:#ffbc0050;letter-spacing:2px}
.pulse{display:inline-block;width:6px;height:6px;border-radius:50%;background:#22c55e;margin-right:6px;animation:pulse 2s infinite}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.3}}
</style>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@300;400&family=Noto+Serif+KR:wght@300;700&display=swap" rel="stylesheet">
<div class="wrap">

  <div class="header">
    <div class="avatar">
      <svg viewBox="0 0 36 36" fill="none">
        <circle cx="18" cy="18" r="16" stroke="#ffbc0030" stroke-width="1"/>
        <circle cx="18" cy="18" r="10" stroke="#ffbc0050" stroke-width="0.8"/>
        <circle cx="18" cy="18" r="4" fill="#ffbc0025" stroke="#ffbc0080" stroke-width="1"/>
        <circle cx="18" cy="18" r="1.5" fill="#ffbc00"/>
        <line x1="2" y1="18" x2="12" y2="18" stroke="#ffbc0030" stroke-width="0.8"/>
        <line x1="24" y1="18" x2="34" y2="18" stroke="#ffbc0030" stroke-width="0.8"/>
        <line x1="18" y1="2" x2="18" y2="12" stroke="#ffbc0030" stroke-width="0.8"/>
        <line x1="18" y1="24" x2="18" y2="34" stroke="#ffbc0030" stroke-width="0.8"/>
      </svg>
    </div>
    <div class="header-text">
      <div class="team-name">끝까지 간다</div>
      <div class="project-name">INCIDENT  AUTOPSY  AGENT</div>
      <div class="desc">장애 원인을 끝까지 추적합니다.<br>AWS Bedrock Claude 기반 RCA 자동 분석 에이전트.</div>
      <div class="badges">
        <span class="badge badge-gold">AWS Bedrock</span>
        <span class="badge badge-gold">Claude Agent</span>
        <span class="badge badge-blue">Spring Boot</span>
        <span class="badge badge-blue">Jennifer APM</span>
        <span class="badge badge-gray">KB데이타시스템 AI LAB 2026</span>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-label">01 &nbsp; project stats</div>
    <div class="stat-grid">
      <div class="stat-card">
        <div class="stat-num red">2~3일</div>
        <div class="stat-label">기존 RCA 작성 시간</div>
      </div>
      <div class="stat-card">
        <div class="stat-num gold">30분</div>
        <div class="stat-label">목표 분석 시간</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">4명</div>
        <div class="stat-label">팀 구성</div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-label">02 &nbsp; tech stack</div>
    <div class="stack-list">
      <div class="stack-item">
        <div class="stack-name">AWS Bedrock Claude</div>
        <div class="stack-bar-wrap"><div class="stack-bar" style="width:100%;background:#ffbc00"></div></div>
        <div class="stack-role">AI 에이전트 코어</div>
      </div>
      <div class="stack-item">
        <div class="stack-name">Spring Boot</div>
        <div class="stack-bar-wrap"><div class="stack-bar" style="width:85%;background:#4080c0"></div></div>
        <div class="stack-role">백엔드 API</div>
      </div>
      <div class="stack-item">
        <div class="stack-name">Jennifer APM</div>
        <div class="stack-bar-wrap"><div class="stack-bar" style="width:70%;background:#30a060"></div></div>
        <div class="stack-role">로그 데이터 소스</div>
      </div>
      <div class="stack-item">
        <div class="stack-name">AWS Lambda · S3</div>
        <div class="stack-bar-wrap"><div class="stack-bar" style="width:75%;background:#4080c0"></div></div>
        <div class="stack-role">서버리스 · 저장</div>
      </div>
      <div class="stack-item">
        <div class="stack-name">React</div>
        <div class="stack-bar-wrap"><div class="stack-bar" style="width:60%;background:#7060c0"></div></div>
        <div class="stack-role">대시보드 UI</div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-label">03 &nbsp; team</div>
    <div class="team-grid">
      <div class="team-card">
        <div class="team-role">AI · 인프라</div>
        <div style="font-family:'IBM Plex Mono',monospace;font-size:12px;color:#c8c4bc">에이전트 설계</div>
        <div class="team-skills">
          <span class="skill-tag">Bedrock</span>
          <span class="skill-tag">Spring Boot</span>
          <span class="skill-tag">S3</span>
        </div>
      </div>
      <div class="team-card">
        <div class="team-role">백엔드 · 인프라</div>
        <div style="font-family:'IBM Plex Mono',monospace;font-size:12px;color:#c8c4bc">파이프라인 · 문서화</div>
        <div class="team-skills">
          <span class="skill-tag">Backend</span>
          <span class="skill-tag">Infra</span>
          <span class="skill-tag">Docs</span>
        </div>
      </div>
      <div class="team-card">
        <div class="team-role" style="color:#30d158">RCA 도메인</div>
        <div style="font-family:'IBM Plex Mono',monospace;font-size:12px;color:#c8c4bc">보고서 구조 · 검수</div>
        <div class="team-skills">
          <span class="skill-tag">RCA</span>
          <span class="skill-tag">장애 대응</span>
          <span class="skill-tag">도메인</span>
        </div>
      </div>
      <div class="team-card">
        <div class="team-role" style="color:#409cff">프론트 · 발표</div>
        <div style="font-family:'IBM Plex Mono',monospace;font-size:12px;color:#c8c4bc">대시보드 · 피칭</div>
        <div class="team-skills">
          <span class="skill-tag">React</span>
          <span class="skill-tag">UI/UX</span>
          <span class="skill-tag">발표</span>
        </div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-label">04 &nbsp; roadmap</div>
    <div class="timeline">
      <div class="tl-item">
        <div class="tl-week">WEEK 1~2</div>
        <div class="tl-text active">▶ Bedrock 연동 + 합성 로그 완성</div>
      </div>
      <div class="tl-item">
        <div class="tl-week">WEEK 3~4</div>
        <div class="tl-text">RCA 리포트 자동 생성 + 제니퍼 연동</div>
      </div>
      <div class="tl-item">
        <div class="tl-week">WEEK 5~6</div>
        <div class="tl-text">프론트 대시보드 + 수치 측정</div>
      </div>
      <div class="tl-item">
        <div class="tl-week">WEEK 7~8</div>
        <div class="tl-text">발표 준비 + 최종 데모</div>
      </div>
    </div>
  </div>

  <div class="footer">
    <div class="footer-left"><span class="pulse"></span>진행 중 · KB데이타시스템 AI LAB 해커톤 2026</div>
    <div class="footer-right">끝까지 간다 →</div>
  </div>

</div>
