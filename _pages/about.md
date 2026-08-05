---
layout: about
title: about
permalink: /
subtitle: Undergraduate Researcher in AI @ Seoul National University

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>SNU PI Lab</p>
    <p>Seoul, South Korea</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  body.fixed-top-nav {
    padding-top: 0 !important;
  }

  body > header {
    display: none !important;
  }

  article > .profile {
    width: 180px !important;
    max-width: 28%;
  }

  .home-sections {
    clear: both;
    padding-top: 1rem;
  }

  .home-sections h2 {
    margin-top: 1.8rem;
  }

  .home-sections h2:first-child {
    margin-top: 0;
  }

  .home-sections .news th::before {
    content: "\2022";
    display: inline-block;
    margin-right: 0.45rem;
  }

  .profile-links {
    margin-top: 0.75rem;
  }

  .profile-links a {
    margin-right: 0.75rem;
  }

  .publication-toolbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
    margin: 0.35rem 0 1.15rem;
  }

  .publication-note {
    margin: 0;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
  }

  .publication-toggle {
    display: inline-flex;
    gap: 0.3rem;
    margin: 0;
    padding: 0.15rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background: var(--global-card-bg-color);
  }

  .publication-toggle button {
    border: 0;
    border-radius: 6px;
    background: transparent;
    color: var(--global-text-color);
    padding: 0.42rem 0.95rem;
    cursor: pointer;
    font-weight: 600;
    line-height: 1.2;
  }

  .publication-toggle button[aria-selected="true"] {
    background: var(--global-theme-color);
    color: var(--global-bg-color);
  }

  .publication-panel[hidden] {
    display: none;
  }

  .publication-panel.publications {
    margin-top: 0;
  }

  .publication-panel ol.bibliography {
    margin: 0;
  }

  .publication-panel ol.bibliography > li {
    margin-bottom: 1.35rem;
  }

  .publication-panel ol.bibliography > li > .row {
    display: grid;
    grid-template-columns: minmax(160px, 28%) minmax(0, 1fr);
    gap: 1.35rem;
    align-items: start;
    margin: 0;
  }

  .publication-panel ol.bibliography > li > .row > .abbr,
  .publication-panel ol.bibliography > li > .row > [id] {
    flex: none;
    width: auto;
    max-width: none;
    padding: 0;
  }

  .publication-panel ol.bibliography .abbr {
    margin: 0;
  }

  .publication-panel ol.bibliography .abbr figure {
    margin: 0;
  }

  .publication-panel ol.bibliography .preview {
    display: block;
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: contain;
    background: #fff;
    border-radius: 8px !important;
    box-shadow: 0 10px 24px rgba(0, 0, 0, 0.16);
  }

  .publication-panel ol.bibliography .title {
    margin-bottom: 0.55rem;
    color: var(--global-text-color);
    font-size: 1.15rem;
    font-weight: 700;
    line-height: 1.25;
  }

  .publication-panel ol.bibliography .title a {
    color: inherit;
    text-decoration: none;
  }

  .publication-panel ol.bibliography .title a:hover {
    color: var(--global-theme-color);
  }

  .publication-panel ol.bibliography .author {
    margin-bottom: 0.65rem;
    color: var(--global-text-color-light);
    font-size: 0.98rem;
    line-height: 1.55;
  }

  .publication-panel ol.bibliography .author > em {
    color: var(--global-text-color);
    font-style: normal;
    font-weight: 700;
    border-bottom: 0;
  }

  .publication-panel ol.bibliography .periodical {
    margin-bottom: 0.7rem;
    color: var(--global-text-color);
    font-size: 1rem;
  }

  .publication-panel ol.bibliography .periodical em {
    font-style: normal;
    font-weight: 700;
  }

  .publication-panel ol.bibliography .links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    margin-top: 0.7rem;
  }

  .publication-panel ol.bibliography .links:empty {
    display: none;
  }

  .publication-panel ol.bibliography .links a.btn {
    margin: 0;
    padding: 0.32rem 0.72rem;
    border: 0;
    border-radius: 999px;
    background: rgba(128, 128, 128, 0.12);
    color: var(--global-text-color);
    font-size: 0.9rem;
    font-weight: 600;
  }

  .publication-panel ol.bibliography .links a.btn:hover {
    background: var(--global-theme-color);
    color: var(--global-bg-color);
  }

  .publication-panel ol.bibliography .links a[href*="arxiv.org"] {
    order: 1;
  }

  .publication-panel ol.bibliography .links a.abstract {
    order: 2;
  }

  .publication-panel ol.bibliography .links a[href*="project-espada.github.io"] {
    order: 3;
  }

  .publication-panel ol.bibliography .links a.bibtex {
    order: 4;
  }

  @media (max-width: 575.98px) {
    article > .profile {
      width: 145px !important;
      max-width: 45%;
    }

    .publication-toolbar {
      align-items: stretch;
      flex-direction: column;
    }

    .publication-toggle {
      width: 100%;
    }

    .publication-toggle button {
      flex: 1;
    }

    .publication-panel ol.bibliography > li > .row {
      grid-template-columns: 1fr;
      gap: 0.9rem;
    }
  }
</style>

<p>
  I am an undergraduate researcher in AI at Seoul National University.<br>
  I am currently a research intern at SNU PI Lab, led by Prof. Youngjae Yu.
</p>

<p>I work on video understanding and enhancing visual representations for robotics,<br>
  with the goal of providing AI better perception capability of physical world.
</p>

<p class="profile-links">
  <a href="mailto:leejangha1257@snu.ac.kr">Email</a>
  <a href="https://www.linkedin.com/in/jangha-lee-441b4433a/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
  <a href="https://scholar.google.com/citations?user=ozXtVR4AAAAJ" target="_blank" rel="noopener noreferrer">Scholar</a>
  <a href="{{ '/assets/pdf/jangha_lee_cv.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">CV</a>
</p>

<div class="home-sections">

<h2 id="news">News</h2>

{% include news.liquid limit=true %}

<h2 id="publications">Publications</h2>

<div class="publication-toolbar">
  <p class="publication-note">(* denotes equal contribution)</p>
  <div class="publication-toggle" role="tablist" aria-label="Publication filter">
    <button id="pub-tab-selected" type="button" role="tab" aria-controls="pub-panel-selected" aria-selected="true">Selected</button>
    <button id="pub-tab-all" type="button" role="tab" aria-controls="pub-panel-all" aria-selected="false">All Publications</button>
  </div>
</div>

<div id="pub-panel-selected" class="publication-panel publications" role="tabpanel" aria-labelledby="pub-tab-selected">
  {% bibliography --group_by none --query @*[selected=true && hidden!=true]* --prefix selected-pubs %}
</div>

<div id="pub-panel-all" class="publication-panel publications" role="tabpanel" aria-labelledby="pub-tab-all" hidden>
  {% bibliography --group_by none --query @*[hidden!=true]* --prefix all-pubs %}
</div>

<script>
  (() => {
    const tabs = document.querySelectorAll(".publication-toggle [role='tab']");
    const panels = document.querySelectorAll(".publication-panel");
    const titleLinks = {
      kim2026espada: "https://project-espada.github.io/espada/",
    };

    tabs.forEach((tab) => {
      tab.addEventListener("click", () => {
        tabs.forEach((item) => item.setAttribute("aria-selected", String(item === tab)));
        panels.forEach((panel) => {
          panel.hidden = panel.id !== tab.getAttribute("aria-controls");
        });
      });
    });

    Object.entries(titleLinks).forEach(([paperId, url]) => {
      document.querySelectorAll(`.publication-panel #${paperId} .title`).forEach((title) => {
        if (title.querySelector("a")) return;
        const link = document.createElement("a");
        link.href = url;
        link.target = "_blank";
        link.rel = "noopener noreferrer";
        link.textContent = title.textContent;
        title.textContent = "";
        title.appendChild(link);
      });
    });

    document.querySelectorAll(".publication-panel .links").forEach((links) => {
      links.querySelectorAll("a.abstract").forEach((link) => {
        link.textContent = "TL;DR";
      });

      const preferredOrder = ["arXiv", "TL;DR", "Website", "Bib"];
      preferredOrder.forEach((label) => {
        Array.from(links.querySelectorAll("a")).forEach((link) => {
          if (link.textContent.trim() === label) links.appendChild(link);
        });
      });
    });
  })();
</script>

<h2 id="industry-experience">Industry Experience</h2>

{% assign industry_experience_page = site.pages | where: "permalink", "/industry-experience/" | first %}
{{ industry_experience_page.content | markdownify }}

<h2 id="education">Education</h2>

{% assign education_page = site.pages | where: "permalink", "/education/" | first %}
{{ education_page.content | markdownify }}

</div>
