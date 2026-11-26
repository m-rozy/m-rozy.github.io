---
title: ""
summary: ""
date: "2022-10-24"
type: "landing"
sections:
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ""
        education: ""
        interests: ""
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |-
        <style>
          .rozy-hub { max-width: 1080px; margin: 0 auto; font-family: inherit; }
          .rozy-hub-header { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 12px; margin-bottom: 20px; padding: 12px 18px; border-radius: 14px; background: rgba(245, 158, 11, 0.08); border: 1px solid rgba(245, 158, 11, 0.22); }
          .rozy-hub-label { font-size: 0.78rem; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase; color: #fb923c; }
          .rozy-hub-badges { display: flex; flex-wrap: wrap; gap: 8px; }
          .rozy-badge { font-size: 0.75rem; font-weight: 600; padding: 4px 10px; border-radius: 999px; background: rgba(255, 255, 255, 0.06); color: #e2e8f0; border: 1px solid rgba(255, 255, 255, 0.1); }
          .rozy-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 18px; }
          .rozy-hub a.rozy-card { text-decoration: none !important; display: flex; flex-direction: column; justify-content: space-between; padding: 24px; border-radius: 18px; background: rgba(15, 23, 42, 0.65); border: 1px solid rgba(255, 255, 255, 0.09); box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2); transition: transform 0.25s ease, border-color 0.25s ease, background 0.25s ease; }
          .rozy-hub a.rozy-card:hover { transform: translateY(-4px); border-color: rgba(251, 146, 60, 0.55); background: rgba(30, 41, 59, 0.85); }
          .rozy-card-top { display: flex; align-items: center; justify-content: space-between; margin-bottom: 14px; }
          .rozy-icon-box { width: 38px; height: 38px; border-radius: 10px; display: flex; align-items: center; justify-content: center; background: rgba(251, 146, 60, 0.14); color: #fb923c; font-weight: 700; font-size: 1.05rem; }
          .rozy-tag { font-size: 0.72rem; font-weight: 600; color: #94a3b8; letter-spacing: 0.04em; }
          .rozy-card h3 { margin: 0 0 8px 0 !important; font-size: 1.12rem !important; font-weight: 700 !important; color: #f8fafc !important; line-height: 1.35 !important; }
          .rozy-card p { margin: 0 0 18px 0 !important; font-size: 0.875rem !important; line-height: 1.6 !important; color: #cbd5e1 !important; }
          .rozy-pill { align-self: flex-start; display: inline-flex; align-items: center; gap: 6px; padding: 6px 14px; border-radius: 999px; font-size: 0.8rem; font-weight: 600; color: #fb923c; background: rgba(251, 146, 60, 0.1); border: 1px solid rgba(251, 146, 60, 0.25); transition: background 0.2s ease, color 0.2s ease; }
          .rozy-hub a.rozy-card:hover .rozy-pill { background: #ea580c; color: #ffffff; border-color: #ea580c; }
        </style>
        <div class="rozy-hub not-prose">
          <div class="rozy-hub-header">
            <span class="rozy-hub-label">Core Focus &amp; Track Record</span>
            <div class="rozy-hub-badges">
              <span class="rozy-badge">10+ Gold Medals</span>
              <span class="rozy-badge">10+ Silver Medals</span>
              <span class="rozy-badge">20+ Bronze Medals</span>
              <span class="rozy-badge">Primary &ndash; Senior High</span>
            </div>
          </div>
          <div class="rozy-grid">
            <a href="#experience" class="rozy-card">
              <div>
                <div class="rozy-card-top">
                  <div class="rozy-icon-box">&Sigma;</div>
                </div>
                <h3>International Olympiad Coaching</h3>
                <p>Intensive problem-solving training for HKIMO, AMO, SASMO, SEAMO, JISMO, and national mathematics competitions.</p>
              </div>
              <span class="rozy-pill">Coaching Track &rarr;</span>
            </a>
            <a href="#experience" class="rozy-card">
              <div>
                <div class="rozy-card-top">
                  <div class="rozy-icon-box">&Delta;</div>
                </div>
                <h3>School &amp; Cambridge Curricula</h3>
                <p>Personalized concept mastery and exam preparation across national and international school mathematics syllabi.</p>
              </div>
              <span class="rozy-pill">Teaching History &rarr;</span>
            </a>
            <a href="#resources" class="rozy-card">
              <div>
                <div class="rozy-card-top">
                  <div class="rozy-icon-box">&int;</div>
                  <span class="rozy-tag">LATEX &amp; TIKZ VAULT</span>
                </div>
                <h3>Modules &amp; Past Paper Sets</h3>
                <p>Tiered worksheets, geometric TikZ diagrams, and curated competition handouts built for structured learning.</p>
              </div>
              <span class="rozy-pill">Browse Materials &rarr;</span>
            </a>
          </div>
        </div>
    design:
      columns: "1"

  - block: resume-experience
    id: experience
    content:
      title: Teaching Experience
      username: me
    design:
      columns: "1"

  - block: collection
    id: resources
    content:
      title: Modules & Resources
      text: ""
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
- block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: compact
---
