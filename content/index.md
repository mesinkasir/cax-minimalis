---
layout: minimalis.cax
title: "CAX SSG - Static Site Generator in Pure C"
description: "Build static sites at lightning speed. Zero dependencies, pure C, no runtime overhead."
icon: /img/icon/hero.svg
hero:
  title: "CAX - The C SSG"
  image: /img/icon/info.svg
  description: "The fastest static site generator built in pure C. No Node.js, No Go, No Rust - just raw C performance."
  text: "Single 400KB binary. No node_modules. Jekyll-style frontmatter, Liquid-like templating, collection controllers, pagination and tags built-in. From zero to live in milliseconds."
  button1:
    text: "Get Started"
    url: "https://cax.axcora.com"
  button2:
    text: "View on GitHub"
    url: "https://github.com/mesinkasir/cax-minimalis"
intro:
  title: "Why Choose C for Static Sites?"
  image: /img/icon/hero.svg
  description: "1972 Power, 2026 Developer Experience"
  text: "We love Jekyll and Eleventy DX, but hate waiting 12 seconds for build. CAX brings elegant frontmatter experience to pure C - with mmap file reading, arena allocation, and zero GC pauses. It's like having a superpower."
card_info:
  - title: "Blazing Fast Build Times"
    image: /img/icon/stack.svg
    description: "0.4s for 1000 Pages"
    text: "Direct memory mapping and custom string pool. Benchmark: CAX 0.4s, Hugo 0.8s, Eleventy 12s. Same site, real test. C wins every time."
  - title: "Familiar Jekyll & 11ty DX"
    image: /img/icon/run.svg
    description: "Same API, Better Speed"
    text: "Nested frontmatter hero.title, button.text, collection controllers via content/minimal.md, smart pagination without /page/1/ bug, {{ tags }}, {% for %}, {% if %} - all implemented in pure C."
  - title: "Single Binary, Zero Dependencies"
    image: /img/icon/binar.svg
    description: "<500KB Binary"
    text: "No libyaml, no dependencies. Just gcc and make. Runs on Windows, Linux, Mac, Raspberry Pi, even your toaster. Copy binary and build anywhere."
footer:
  title: "Ready to Build at C Speed?"
  image: /img/icon/ready.svg
  description: "Join 500+ devs who ditched JS tooling for pure C."
  text: "MIT Licensed. Built by Axcora Technology. Custom artisan web at axcora.com - Fiverr gigs at fiverr.com/creativitas"
update:
  title: "Lastest Posts"
  image: /img/icon/post.svg
  button:
    text: "Explore All Articles"
    url: /posts/

---

## Quick Start - 20 Seconds

```bash
git clone https://github.com/mesinkasir/cax-minimalis
cd cax-minimalis
make
./cax build
./cax start
```

Open `http://localhost:8080` - LiveReload is built-in with 100 lines of C.


### Why CAX Minimalis Starter?

This starter is production-ready for your blog, portfolio, or docs. Pre-configured with:

+ Axcora CSS - 12KB modern CSS, no Bootstrap bloat
+ SEO Ready - `sitemap.xml`, `rss.xml`, `feed.json`, `robots.txt` auto-generated
+ Pretty URLs - `/minimal/my-post/` not `/minimal/my-post.html`
+ Data Driven - Just edit `_data/metadata.json` or `_data/social.yaml` and use `{{ metadata.title }}`
