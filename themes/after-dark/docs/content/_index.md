+++
title = "After Dark"
description = "After Dark is a hypermedia authoring toolkit built with Hugo designed to create the world's fastest, most scalable websites imaginable."
images = [
  "https://after-dark.habd.as/images/screenshots/example-landing-page-fs8.png"
]
+++

<section class="grid logo">
  <div class="cell -12of12">
    <svg class="shaded animated" viewBox="0 0 46 45" width="92" height="90" xmlns="http://www.w3.org/2000/svg">
      <title>After Dark</title>
      <path d="M.708 45L23 .416 45.292 45H.708zM35 38L23 19 11 38h24z" fill="#000"/>
    </svg>
  </div>
</section>

<section class="grid tagline">
  <div class="cell -12of12">
    <p>After Dark is a hypermedia authoring toolkit built with Hugo designed to create the world's fastest, most scalable websites imaginable.</p>
  </div>
</section>

<section class="hero">
  <style>
    a[target=_self] {
      border-bottom: unset;
    }
    a[target=_self]:hover {
      background-color: transparent;
    }
    button.btn.btn-ghost.btn-primary {
      border-radius: 4px;
      color: #ccc;
      background-color: #ff2e8860;
      border: unset;
      transition: all 0.25s ease;
    }
    button.btn.btn-ghost.btn-primary:hover {
      background-color: #ff2e8880;
      color: #fff;
    }
    button.btn.btn-ghost.btn-primary svg {
      stroke: #ff9800;
    }
  </style>
  {{< external rel="noopener" target="_self" href="/feature/quick-install/" >}}
    {{< hackcss-button type="primary" isghost="true" >}}
      <svg class="i-download" viewBox="0 0 32 32" width="24" height="24" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
        <path d="M9 22 C0 23 1 12 9 13 6 2 23 2 22 10 32 7 32 23 23 22 M11 26 L16 30 21 26 M16 16 L16 30"></path>
      </svg>&nbsp;&nbsp;Quick Install
    {{< /hackcss-button >}}
  {{< /external >}}
  <!-- <svg viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M30 10 L16 26 2 10 Z" />
  </svg>
  <svg viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M30 10 L16 26 2 10 Z" />
  </svg>
  <svg viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M30 10 L16 26 2 10 Z" />
  </svg> -->
  {{< figure alt="After Dark screenshots" src="/images/minimal-mac_1600x1200-fs8.png" lqipsrc="/images/minimal-mac_800x600-fs8.png" >}}
</section>

<section class="capabilities">
  <svg id="i-options" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M28 6 L4 6 M28 16 L4 16 M28 26 L4 26 M24 3 L24 9 M8 13 L8 19 M20 23 L20 29" />
  </svg>
  <h2>Beyond Compare</h2>
  <table>
    <legend>Reimagine your publishing workflow with an array of capabilities specifically designed to greatly simplify site maintenance and speed-up content delivery:</legend>
    <tr>
      <th scope="col" width="25%">Features</th>
      <th scope="col" width="25%">Modules</th>
      <th scope="col" width="25%">Shortcodes</th>
      <th scope="col" width="25%">Extras</th>
    </tr>
    <tr>
      <td><a href="./feature/">33</a></td>
      <td><a href="./module/">4</a></td>
      <td><a href="./shortcode/">23</a></td>
      <td><a href="./extra/">1</a></td>
    </tr>
  </table>
</section>

<section id="feature-mining" class="feature">
  <svg id="i-creditcard" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M2 7 L2 25 30 25 30 7 Z M5 18 L9 18 M5 21 L11 21" />
    <path d="M2 11 L2 13 30 13 30 11 Z" fill="currentColor" />
  </svg>
  <h2 style="margin-bottom:0.2rem">Web Mining</h2>
  <small><i style="color:lime">(Now in Beta!)</i></small>
  <p>Earn incentives for staying up-to-date and reward your creativity throughout the entire content publishing lifecycle, start to finish.</p>
  <nav><p>
    <a href="/module/toxic-swamp/">Get Started</a> |
    <a href="/module/toxic-swamp/#config-generator">Generate Config</a>
  </p></nav>
</section>

<section class="feature">
  <svg id="feature-graphics" id="i-photo" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M20 24 L12 16 2 26 2 2 30 2 30 24 M16 20 L22 14 30 22 30 30 2 30 2 24" />
    <circle cx="10" cy="9" r="3" />
  </svg>
  <h2>Unreal Graphics</h2>
  <p>Create lazy-loading responsive images and galleries with low-quality image placeholders and special effects without even touching an image editor.</p>
  <nav><p>
    <a href="/shortcode/figure/">Figures</a> |
    <a href="/feature/post-images/">Post Images</a> |
    <a href="/module/hall-of-mirrors/">Galleries</a> |
    <a href="/module/fractal-forest/">BPG</a>
  </p></nav>
</section>

<section id="feature-speed" class="feature">
  <svg class="i-lightning" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M18 13 L26 2 8 13 14 19 6 30 24 19 Z" />
  </svg>
  <h2>Ludicrous Speed</h2>
  <p>Load pages over the wire in milliseconds without relying on complex build systems and generate over 1000 pages per second using commodity hardware.</p>
  <nav><p>
    <a href="/feature/fetch-injection/">Fetch Inject</a> |
    <a href="/feature/lazy-loading/">Lazy Load</a> |
    <a href="/feature/jit-requests/">JIT Requests</a>
  </p></nav>
</section>

<section id="feature-customize" class="feature">
  <svg id="i-compose" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M27 15 L27 30 2 30 2 5 17 5 M30 6 L26 2 9 19 7 25 13 23 Z M22 6 L26 10 Z M9 19 L13 23 Z" />
  </svg>
  <h2>Fully Customizable</h2>
  <p>Toggle between 1 of 8 customizable skin styles or disable them entirely and use custom layouts and styles to take complete design control.</p>
  <nav><p>
    <a href="/feature/skin-styles/">Skins</a> |
    <a href="/feature/custom-layouts/">Layouts</a> |
    <a href="/feature/custom-styles/">Styles</a> |
    <a href="/feature/svg-favicon/">Favicons</a>
  </p></nav>
</section>

<section id="feature-search" class="feature">
  <svg id="i-search" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <circle cx="14" cy="14" r="12" />
    <path d="M23 23 L30 30"  />
  </svg>
  <h2>Offline Search</h2>
  <p>Locate content crawlable by search engines anywhere on your site instantly, even without an Internet connection. No registration required.</p>
  <nav><p>
    <a href="/feature/fuzzy-search/">Fuzzy Search</a> |
    <a href="/shortcode/form/">Form Controls</a> |
    <a href="/search/?s=lay%20load">Try It Now</a>
  </p></nav>
</section>

<section id="feature-security" class="feature">
  <svg id="i-lock" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
    <path d="M5 15 L5 30 27 30 27 15 Z M9 15 C9 9 9 5 16 5 23 5 23 9 23 15 M16 20 L16 23" />
    <circle cx="16" cy="24" r="1" />
  </svg>
  <h2>Securely Designed</h2>
  <p>Verify you are using a genuine After Dark release online or off using secure cryptographic release hashes and upgrade your site remotely in seconds.</p>
  <nav><p>
    <a href="/validate/">Validate</a> |
    <a href="/feature/upgrade-script/">Upgrade</a> |
    <a href="/feature/release-hashes/">Learn More</a>

  </p></nav>
</section>

<footer>
  <section class="grid cta">
    <div class="cell -2of12">
      {{< external rel="prefetch" target="_self" itemtype="significantLink" href="https://git.habd.as/comfusion/after-dark/activity" >}}
        <svg id="activity" aria-labelledby="activity-label" class="i-activity" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
          <path d="M4 16 L11 16 14 29 18 3 21 16 28 16" />
        </svg>
        <small role="tooltip" id="activity-label">Activity</small>
      {{< /external >}}
    </div>
    <div class="cell -2of12">
      {{< external rel="prefetch" target="_self" itemtype="significantLink" href="https://git.habd.as/comfusion/after-dark/" >}}
        <svg id="source" aria-labelledby="source-label" class="i-code" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
          <path d="M10 9 L3 17 10 25 M22 9 L29 17 22 25 M18 7 L14 27" />
        </svg>
        <small role="tooltip" id="source-label">Source</small>
      {{< /external >}}
    </div>
    <div class="cell -2of12">
      {{< external rel="noopener" itemtype="significantLink" href="https://t.me/comfusion" >}}
        <svg id="telegram" aria-labelledby="telegram-label" class="i-send" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
          <path d="M2 16 L30 2 16 30 12 20 Z M30 2 L12 20" />
        </svg>
        <small role="tooltip" id="telegram-label">Telegram</small>
      {{< /external >}}
    </div>
    <div class="cell -2of12">
      {{< external title="Download" rel="prefetch" target="_self" itemtype="significantLink" href="https://git.habd.as/comfusion/after-dark/#getting-started" >}}
        <svg id="download" aria-labelledby="download-label" class="i-download" viewBox="0 0 32 32" width="32" height="32" fill="none" stroke="currentcolor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
          <path d="M9 22 C0 23 1 12 9 13 6 2 23 2 22 10 32 7 32 23 23 22 M11 26 L16 30 21 26 M16 16 L16 30" />
        </svg>
        <small role="tooltip" id="download-label">Download</small>
      {{< /external >}}
    </div>
  </section>

  <section class="grid license">
    <div class="cell -12of12">
      {{< external rel="noopener license" href="https://choosealicense.com/licenses/wtfpl/" >}}
        <img width="48" src="/images/wtfpl.svg" alt="WTFPL logo" title="After Dark is gratis under WTFPL license.">
      {{< /external >}}
    </div>
  </section>
</footer>