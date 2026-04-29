# jessicahenlan.github.io
Jessica Henlan Content Creation Rate Card
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jessica Henlan — Rate Card</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&family=Bodoni+Moda:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
<style>
  :root {
    --white: #FFFFFF;
    --off: #F7F7F5;
    --charcoal: #1C1C1C;
    --mid: #636360;
    --rule: #E2E2DE;
    --accent: #C8C4BC;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--white);
    color: var(--charcoal);
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 12.5px;
    line-height: 1.65;
    -webkit-font-smoothing: antialiased;
  }

  .page {
    max-width: 800px;
    margin: 0 auto;
    padding: 60px 60px 72px;
  }

  /* ── HEADER ── */
  .header {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    padding-bottom: 22px;
    border-bottom: 2px solid var(--charcoal);
    margin-bottom: 48px;
  }

  .name {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    font-size: 44px;
    line-height: 1;
    letter-spacing: 0.02em;
    color: var(--charcoal);
  }

  .subtitle {
    font-family: 'Montserrat', sans-serif;
    font-weight: 500;
    font-size: 8px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--mid);
    text-align: right;
    line-height: 1.8;
  }

  /* ── SECTION ── */
  .section {
    margin-bottom: 44px;
  }

  .section-header {
    display: flex;
    align-items: center;
    gap: 16px;
    margin-bottom: 20px;
  }

  .section-label {
    font-weight: 700;
    font-size: 11px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--charcoal);
    white-space: nowrap;
  }

  .section-rule {
    flex: 1;
    height: 1px;
    background: var(--rule);
  }

  .section-intro {
    font-size: 11.5px;
    color: var(--charcoal);
    line-height: 1.8;
    margin-bottom: 22px;
    font-weight: 400;
  }

  /* ── TWO-COL VIDEO PRICING ── */
  .two-col {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }

  .pricing-col {
    padding-right: 36px;
  }

  .pricing-col + .pricing-col {
    padding-right: 0;
    padding-left: 36px;
    border-left: 1px solid var(--rule);
  }

  .col-tag {
    font-size: 7.5px;
    font-weight: 700;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 6px;
  }

  .col-title {
    font-weight: 700;
    font-size: 13px;
    letter-spacing: 0.04em;
    text-transform: uppercase;
    margin-bottom: 4px;
  }

  .col-desc {
    font-size: 11px;
    color: var(--charcoal);
    line-height: 1.65;
    font-weight: 400;
    margin-bottom: 16px;
  }

  .price-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 9px 0;
    border-bottom: 1px solid var(--rule);
  }

  .price-row:first-of-type { border-top: 1px solid var(--rule); }

  .price-label {
    font-size: 12px;
    font-weight: 400;
    color: var(--charcoal);
  }

  .price-amount {
    font-weight: 700;
    font-size: 14px;
    color: var(--charcoal);
    letter-spacing: 0.02em;
  }

  /* ── INCLUDED ── */
  .included-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 0 40px;
  }

  .included-item {
    font-size: 12px;
    font-weight: 400;
    padding: 8px 0;
    border-bottom: 1px solid var(--rule);
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .dot {
    width: 4px;
    height: 4px;
    border-radius: 50%;
    background: var(--charcoal);
    flex-shrink: 0;
  }

  /* ── ADD-ONS / USAGE ── */
  .row {
    display: grid;
    grid-template-columns: 1fr auto;
    align-items: start;
    gap: 24px;
    padding: 11px 0;
    border-bottom: 1px solid var(--rule);
  }

  .row:first-of-type { border-top: 1px solid var(--rule); }

  .row-name {
    font-size: 12.5px;
    font-weight: 600;
    color: var(--charcoal);
    margin-bottom: 2px;
    letter-spacing: 0.01em;
  }

  .row-note {
    font-size: 11px;
    color: var(--charcoal);
    line-height: 1.6;
    font-weight: 400;
  }

  .row-price {
    font-weight: 700;
    font-size: 14px;
    color: var(--charcoal);
    text-align: right;
    white-space: nowrap;
    padding-top: 1px;
  }

  .row-price-sub {
    display: block;
    font-size: 9px;
    font-weight: 500;
    color: var(--mid);
    letter-spacing: 0.08em;
    text-align: right;
    text-transform: uppercase;
    margin-top: 1px;
  }

  /* ── CREATOR AMPLIFICATION ── */
  .amp-box {
    background: var(--off);
    padding: 22px 26px;
  }

  .amp-intro {
    font-size: 11px;
    font-weight: 400;
    color: var(--charcoal);
    font-style: italic;
    margin-bottom: 4px;
  }

  .amp-box .row:first-of-type {
    border-top: 1px solid var(--rule);
  }

  /* ── FOOTER ── */
  .footer {
    margin-top: 0;
    padding-top: 20px;
    border-top: 1px solid var(--rule);
    font-size: 10px;
    font-weight: 400;
    color: var(--charcoal);
    line-height: 1.9;
    text-align: center;
    letter-spacing: 0.01em;
  }

  .section:last-of-type {
    margin-bottom: 20px;
  }
    .page { padding: 44px 48px; }
  }
</style>
</head>
<body>
<div class="page">

  <!-- HEADER -->
  <header class="header">
    <h1 class="name">Jessica Henlan</h1>
    <p class="subtitle">UGC &amp; Lifestyle Content Creator<br>Rate Card &nbsp;·&nbsp; AUD excl. GST</p>
  </header>

  <!-- VIDEO CONTENT -->
  <section class="section">
    <div class="section-header">
      <span class="section-label">Video Content</span>
      <div class="section-rule"></div>
    </div>
    <p class="section-intro">Two content types available. Organic content is lifestyle-driven and built for engagement. Ad-optimised content is strategically structured for performance and conversions. Usage rights are priced separately from content type — see below.</p>
    <div class="two-col">
      <div class="pricing-col">
        <p class="col-title">Organic-Style Content</p>
        <p class="col-desc">Natural, lifestyle-driven. Built for engagement and brand presence.</p>
        <div class="price-row"><span class="price-label">1 video</span><span class="price-amount">$200</span></div>
        <div class="price-row"><span class="price-label">3 videos bundle</span><span class="price-amount">$520</span></div>
        <div class="price-row"><span class="price-label">5 videos bundle</span><span class="price-amount">$850</span></div>
      </div>
      <div class="pricing-col">
        <p class="col-title">Ad-Optimised Content</p>
        <p class="col-desc">Structured for conversions. Strong hooks, intentional pacing, performance-focused.</p>
        <div class="price-row"><span class="price-label">1 video</span><span class="price-amount">$250</span></div>
        <div class="price-row"><span class="price-label">3 videos bundle</span><span class="price-amount">$650</span></div>
        <div class="price-row"><span class="price-label">5 videos bundle</span><span class="price-amount">$1,050</span></div>
      </div>
    </div>
  </section>

  <!-- INCLUDED -->
  <section class="section">
    <div class="section-header">
      <span class="section-label">Included in Every Video</span>
      <div class="section-rule"></div>
    </div>
    <div class="included-grid">
      <div class="included-item"><span class="dot"></span>Concept and creative direction</div>
      <div class="included-item"><span class="dot"></span>Script writing (if not provided)</div>
      <div class="included-item"><span class="dot"></span>Filming and production</div>
      <div class="included-item"><span class="dot"></span>Editing with music and captions</div>
      <div class="included-item"><span class="dot"></span>Two rounds of revisions</div>
      <div class="included-item"><span class="dot"></span>Organic usage included</div>
    </div>
  </section>

  <!-- ADD-ONS -->
  <section class="section">
    <div class="section-header">
      <span class="section-label">Add-Ons</span>
      <div class="section-rule"></div>
    </div>
    <div class="row">
      <div><p class="row-name">Additional hook</p><p class="row-note">Per extra hook variation on an existing video. Useful for ad testing.</p></div>
      <div><p class="row-price">$40<span class="row-price-sub">per hook</span></p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Additional revision round</p><p class="row-note">Beyond the two included rounds.</p></div>
      <div><p class="row-price">$50</p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Raw footage</p><p class="row-note">Unedited files delivered alongside final content.</p></div>
      <div><p class="row-price">$150<span class="row-price-sub">per video</span></p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Script only</p><p class="row-note">Written to your brief. Ready to hand to another creator or use in-house.</p></div>
      <div><p class="row-price">$80</p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Whitelisting</p><p class="row-note">Pricing on application — depends on duration and platform.</p></div>
      <div><p class="row-price">POA</p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Custom package</p><p class="row-note">Retainers, mixed content, or anything not listed above.</p></div>
      <div><p class="row-price">POA</p></div>
    </div>
  </section>

  <!-- CREATOR AMPLIFICATION -->
  <section class="section">
    <div class="section-header">
      <span class="section-label">Creator Amplification</span>
      <div class="section-rule"></div>
    </div>
    <div class="amp-box">
      <p class="amp-intro">These rates cover organic posting to Jessica Henlan's account (@jessh.ica).</p>
      <div class="row" style="border-top: 1px solid var(--rule);">
        <div><p class="row-name">Feed post (Reel or static)</p><p class="row-note">Includes repost to Stories for 24 hours at time of posting. 60 days on feed included.</p></div>
        <div><p class="row-price">$150<span class="row-price-sub">per video</span></p></div>
      </div>
      <div class="row">
        <div><p class="row-name">Stories series</p><p class="row-note">Video content optimised for Stories. Added to Highlights for 60 days.</p></div>
        <div><p class="row-price">$100<span class="row-price-sub">per video</span></p></div>
      </div>
      <div class="row">
        <div><p class="row-name">Extended feed post</p><p class="row-note">Beyond initial 60 days.</p></div>
        <div><p class="row-price">$50<span class="row-price-sub">per month</span></p></div>
      </div>
    </div>
  </section>

  <!-- USAGE RIGHTS -->
  <section class="section">
    <div class="section-header">
      <span class="section-label">Usage Rights</span>
      <div class="section-rule"></div>
    </div>
    <p class="section-intro">Ad-optimised and usage rights are separate charges. Ad-optimised describes how content is made. Usage rights cover how and where it's used. Both can apply to the same piece of content.</p>
    <div class="row" style="border-top: 1px solid var(--rule);">
      <div><p class="row-name">Organic use</p><p class="row-note">Posting on brand's own social channels.</p></div>
      <div><p class="row-price">Included</p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Paid ads — 3 months</p><p class="row-note">Content used in paid social or digital advertising.</p></div>
      <div><p class="row-price">$150<span class="row-price-sub">per video</span></p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Paid ads — 6 months</p><p class="row-note">Extended paid advertising use.</p></div>
      <div><p class="row-price">$250<span class="row-price-sub">per video</span></p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Paid ads — 12 months</p><p class="row-note">Long-term campaign use — based on scope.</p></div>
      <div><p class="row-price">POA</p></div>
    </div>
    <div class="row">
      <div><p class="row-name">Whitelisting</p><p class="row-note">Ads run from creator's account. Platform access required.</p></div>
      <div><p class="row-price">POA</p></div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    All prices in AUD and exclude GST. Rates are a guide — packages are flexible and tailored to your brief. A 50% deposit is required on agreement with the remainder due on final approval. Content licensing is separate from content creation fees. Ownership of all content remains with Jessica Henlan until payment is received in full.
  </footer>

</div>
</body>
</html>
