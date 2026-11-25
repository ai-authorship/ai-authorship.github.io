---
layout: default
title: AI Authorship Labels
description: A clear, adaptable way to tell readers how people and AI contributed to written text.
---

<section class="hero" id="about">
  <div class="hero-copy">
    <p class="eyebrow"><span class="eyebrow-dot"></span> A voluntary disclosure system</p>
    <h1>Make the writing process <em>visible.</em></h1>
    <p class="hero-intro">Simple labels help readers understand whether text was written by a person, AI, or both—and how it was reviewed or translated.</p>
    <div class="hero-actions">
      <a class="button button-light" href="#labels">Explore the labels <span aria-hidden="true">↓</span></a>
      <a class="button button-quiet" href="{{ site.repository_url }}">Adapt the system <span aria-hidden="true">↗</span></a>
    </div>
    <p class="hero-footnote">Use the system as written or adapt it to your own AI writing process.</p>
  </div>
  <aside class="sample-card" aria-label="Example label">
    <div class="sample-card-top"><span class="sample-dot"></span> A label at a glance</div>
    <a class="sample-code" href="{{ '/labels/MA-AR.html' | relative_url }}">MA-AR</a>
    <p class="sample-title">Human and AI co-authored</p>
    <p class="sample-body">Both contributed to the writing. The human co-author and AI reviewed the text.</p>
    <span class="sample-rule"></span>
    <p class="sample-caption">A process description, not a quality score.</p>
  </aside>
  <div class="hero-orb hero-orb-one"></div>
  <div class="hero-orb hero-orb-two"></div>
</section>

<section class="intro-strip">
  <div class="intro-mark">i</div>
  <p><strong>Clear about process.</strong> The labels are optional and self-reported. They do not verify authorship or guarantee accuracy.</p>
  <a href="{{ '/DISCLAIMER.html' | relative_url }}">Read the disclaimer <span aria-hidden="true">→</span></a>
</section>

<section class="label-section" id="labels">
  <div class="section-heading">
    <div>
      <p class="eyebrow eyebrow-dark">The label set</p>
      <h2>Find the closest description.</h2>
    </div>
    <p class="section-note">Start with who wrote the text, then note review and language work.</p>
  </div>

  <div class="label-group">
    <div class="group-heading">
      <span class="group-number">01</span>
      <div><h3>Human-authored</h3><p>Written by a person, with the listed AI assistance.</p></div>
    </div>
    <div class="label-grid">
      <a class="label-card" href="{{ '/labels/HA.html' | relative_url }}"><span class="code code-human">HA</span><span class="card-copy"><strong>Human-authored</strong><small>No AI involvement</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/HA-AT.html' | relative_url }}"><span class="code code-human">HA-AT</span><span class="card-copy"><strong>AI translation</strong><small>Human-written and reviewed</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/HA-AR.html' | relative_url }}"><span class="code code-human">HA-AR</span><span class="card-copy"><strong>AI review</strong><small>Reviewed by human and AI</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/HA-AR-AT.html' | relative_url }}"><span class="code code-human">HA-AR-AT</span><span class="card-copy"><strong>AI review + translation</strong><small>Human-written and reviewed</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/HA-AG.html' | relative_url }}"><span class="code code-human">HA-AG</span><span class="card-copy"><strong>Grammar and proofreading</strong><small>AI corrections only</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/HA-AG-AT.html' | relative_url }}"><span class="code code-human">HA-AG-AT</span><span class="card-copy"><strong>Corrections + translation</strong><small>Human-written and reviewed</small></span><span class="card-arrow">↗</span></a>
    </div>
  </div>

  <div class="label-group">
    <div class="group-heading">
      <span class="group-number">02</span>
      <div><h3>AI-authored</h3><p>Drafted by AI, with human review noted where present.</p></div>
    </div>
    <div class="label-grid label-grid-three">
      <a class="label-card" href="{{ '/labels/AA.html' | relative_url }}"><span class="code code-ai">AA</span><span class="card-copy"><strong>AI-authored</strong><small>No human review indicated</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/AA-HR.html' | relative_url }}"><span class="code code-ai">AA-HR</span><span class="card-copy"><strong>Human-reviewed</strong><small>AI drafted; human adapted</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/AA-HR-AT.html' | relative_url }}"><span class="code code-ai">AA-HR-AT</span><span class="card-copy"><strong>Reviewed + translated</strong><small>AI drafted; human reviewed</small></span><span class="card-arrow">↗</span></a>
    </div>
  </div>

  <div class="label-group">
    <div class="group-heading">
      <span class="group-number">03</span>
      <div><h3>Mixed-authored</h3><p>Both human and AI contributed to the writing.</p></div>
    </div>
    <div class="label-grid">
      <a class="label-card" href="{{ '/labels/MA.html' | relative_url }}"><span class="code code-mixed">MA</span><span class="card-copy"><strong>Mixed-authored</strong><small>Human co-author reviewed</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/MA-AT.html' | relative_url }}"><span class="code code-mixed">MA-AT</span><span class="card-copy"><strong>AI translation</strong><small>Mixed-authored text</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/MA-AR.html' | relative_url }}"><span class="code code-mixed">MA-AR</span><span class="card-copy"><strong>Human and AI review</strong><small>Both contributed to writing</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/MA-AR-AT.html' | relative_url }}"><span class="code code-mixed">MA-AR-AT</span><span class="card-copy"><strong>Review + translation</strong><small>Reviewed by human and AI</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/MA-AG.html' | relative_url }}"><span class="code code-mixed">MA-AG</span><span class="card-copy"><strong>Grammar and proofreading</strong><small>AI corrections only</small></span><span class="card-arrow">↗</span></a>
      <a class="label-card" href="{{ '/labels/MA-AG-AT.html' | relative_url }}"><span class="code code-mixed">MA-AG-AT</span><span class="card-copy"><strong>Corrections + translation</strong><small>Mixed-authored text</small></span><span class="card-arrow">↗</span></a>
    </div>
  </div>

  <div class="label-group label-group-last">
    <div class="group-heading">
      <span class="group-number">04</span>
      <div><h3>Authorship unspecified</h3><p>Translation is disclosed; who wrote the source is not.</p></div>
    </div>
    <div class="label-grid label-grid-three">
      <a class="label-card" href="{{ '/labels/AT.html' | relative_url }}"><span class="code code-translation">AT</span><span class="card-copy"><strong>AI-translated</strong><small>Authorship unspecified</small></span><span class="card-arrow">↗</span></a>
    </div>
  </div>
</section>

<section class="principles" id="principles">
  <div class="principles-heading">
    <p class="eyebrow eyebrow-dark">A simple framework</p>
    <h2>Tell readers what happened.<br><span>Let them decide what it means.</span></h2>
  </div>
  <div class="principle-list">
    <article><span class="principle-index">A</span><div><h3>Describe the process</h3><p>Authorship, review, proofreading, and translation are separate contributions. The codes make those distinctions visible.</p></div></article>
    <article><span class="principle-index">B</span><div><h3>Keep the claim honest</h3><p>Labels are opt-in and unverified. Their usefulness depends on accurate, transparent disclosure.</p></div></article>
    <article><span class="principle-index">C</span><div><h3>Adapt it freely</h3><p>Use this system as a starting point and adapt it for your own way of generating AI content, under CC BY 4.0.</p></div></article>
  </div>
</section>

