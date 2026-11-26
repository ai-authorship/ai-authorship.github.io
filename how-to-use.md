---
layout: default
title: Add a label to your site
description: Copy and adapt HTML snippets that link an AI authorship label to its explanation.
---

<div class="guide-hero">
  <p class="eyebrow eyebrow-dark">Share a disclosure</p>
  <h1>Put the label where readers see it.</h1>
  <p>Embed a small linked label next to the text it describes. The link opens the explanation page, so readers can see what the code means.</p>
</div>

<div class="guide-callout">
  <strong>Use these snippets on sites that allow HTML.</strong>
  <span>Some publishing platforms remove custom HTML or inline styles. If yours does, use a plain text code with a link instead.</span>
</div>

<section class="guide-section">
  <div class="guide-heading">
    <span class="guide-step">01</span>
    <div><h2>Compact label</h2><p>A small badge that fits beside a title, byline, or article footer.</p></div>
  </div>

{% highlight html %}
<a href="{{ site.url }}{{ site.baseurl }}/labels/HA-AR.html"
   aria-label="AI authorship label: HA-AR, human-authored and reviewed by human and AI"
   style="display:inline-flex;padding:.4em .7em;border:1px solid #13744c;border-radius:999px;background:#fff;color:#13744c;font:700 13px/1.2 system-ui,sans-serif;text-decoration:none">
  HA-AR
</a>
{% endhighlight %}

  <div class="guide-preview">
    <p class="guide-preview-label">Rendered example</p>
    <a href="{{ '/labels/HA-AR.html' | relative_url }}"
       aria-label="AI authorship label: HA-AR, human-authored and reviewed by human and AI"
       style="display:inline-flex;padding:.4em .7em;border:1px solid #13744c;border-radius:999px;background:#fff;color:#13744c;font:700 13px/1.2 system-ui,sans-serif;text-decoration:none">
      HA-AR
    </a>
  </div>

  <p class="guide-hint">Change the destination, code, and accessible label to match the label you are using.</p>
</section>

<section class="guide-section">
  <div class="guide-heading">
    <span class="guide-step">02</span>
    <div><h2>Disclosure card</h2><p>A larger, more descriptive card for an article page or publication site.</p></div>
  </div>

{% highlight html %}
<a href="{{ site.url }}{{ site.baseurl }}/labels/MA-AR.html"
   aria-label="AI authorship label: MA-AR, mixed-authored and reviewed by human and AI"
   style="display:flex;align-items:center;gap:14px;max-width:420px;padding:16px 18px;border:1px solid #e5e2ec;border-radius:14px;background:#fff;color:#211e3b;font-family:system-ui,sans-serif;text-decoration:none">
  <span aria-hidden="true"
        style="padding:7px 9px;border-radius:7px;background:#fff;color:#245ca6;border:1px solid #245ca6;font-size:12px;font-weight:800">
    MA-AR
  </span>
  <span style="display:grid;gap:3px">
    <strong style="font-size:14px">Human and AI co-authored</strong>
    <span style="color:#706d7c;font-size:12px">Reviewed by the human co-author and AI</span>
  </span>
  <span aria-hidden="true" style="margin-left:auto;color:#8b8798">↗</span>
</a>
{% endhighlight %}

  <div class="guide-preview">
    <p class="guide-preview-label">Rendered example</p>
    <a href="{{ '/labels/MA-AR.html' | relative_url }}"
       aria-label="AI authorship label: MA-AR, mixed-authored and reviewed by human and AI"
       style="display:flex;align-items:center;gap:14px;max-width:420px;padding:16px 18px;border:1px solid #e5e2ec;border-radius:14px;background:#fff;color:#211e3b;font-family:system-ui,sans-serif;text-decoration:none">
      <span aria-hidden="true"
            style="padding:7px 9px;border-radius:7px;background:#fff;color:#245ca6;border:1px solid #245ca6;font-size:12px;font-weight:800">
        MA-AR
      </span>
      <span style="display:grid;gap:3px">
        <strong style="font-size:14px">Human and AI co-authored</strong>
        <span style="color:#706d7c;font-size:12px">Reviewed by the human co-author and AI</span>
      </span>
      <span aria-hidden="true" style="margin-left:auto;color:#8b8798">↗</span>
    </a>
  </div>

  <p class="guide-hint">Update the code, destination URL, accessible label, title, and short description together so they all describe the same disclosure.</p>
</section>

<section class="guide-section">
  <div class="guide-heading">
    <span class="guide-step">03</span>
    <div><h2>Pick the right destination</h2><p>Each code should link directly to its own explanation.</p></div>
  </div>
  <div class="guide-destination">
    <p>For example, the card above points to the <a href="{{ '/labels/MA-AR.html' | relative_url }}">MA-AR explanation</a>. To use another label, replace <code>MA-AR</code> in the URL with that code and update the text in the card. Browse the <a href="{{ '/' | relative_url }}#labels">full label directory</a>.</p>
    <p>The source-language detail is optional for all translation labels. Label disclosures are also optional and self-reported; the link explains the claim but does not verify it.</p>
  </div>
</section>

<section class="guide-section guide-last">
  <div class="guide-heading">
    <span class="guide-step">04</span>
    <div><h2>Place it beside the text</h2><p>Make the relationship clear to readers.</p></div>
  </div>
  <div class="guide-destination">
    <p>Place the badge or card near the title, byline, or end of the text it describes. Keep it visible and make sure it links to the matching explanation page.</p>
    <p>If a site strips HTML, use plain linked text such as <a href="{{ '/labels/HA-AR.html' | relative_url }}"><strong>HA-AR — Human-authored, AI-reviewed</strong></a>.</p>
  </div>
</section>
