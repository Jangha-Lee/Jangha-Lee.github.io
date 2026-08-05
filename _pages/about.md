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
    <p><a href="https://pi.snu.ac.kr/" target="_blank" rel="noopener noreferrer">SNU PI Lab</a></p>
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

  body > footer {
    display: none !important;
  }

  .post-header {
    margin-bottom: 0.25rem;
  }

  article > .profile {
    width: 180px !important;
    max-width: 28%;
    margin-top: -1.8rem;
    margin-bottom: 0.2rem;
  }

  .home-sections {
    clear: both;
    margin-top: -1.45rem;
    padding-top: 0;
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

  .publication-panel #lee2026ownership .author,
  .publication-panel #lee2026refineground .author {
    display: none;
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
    display: none;
  }

  .publication-panel ol.bibliography .links a[href*="project-espada.github.io"] {
    order: 2;
  }

  .publication-panel ol.bibliography .links a.bibtex {
    order: 3;
  }

  .publication-tldr {
    margin-top: 0.75rem;
    padding-left: 0.75rem;
    border-left: 3px solid var(--global-theme-color);
    color: var(--global-text-color-light);
    font-size: 0.95rem;
    line-height: 1.55;
  }

  .publication-tldr p {
    margin: 0;
  }

  .publication-tldr-label {
    color: var(--global-text-color);
    font-weight: 700;
  }

  .publication-tldr-more[hidden] {
    display: none;
  }

  .publication-tldr-toggle {
    margin-left: 0.35rem;
    padding: 0;
    border: 0;
    background: transparent;
    color: var(--global-theme-color);
    cursor: pointer;
    font: inherit;
    font-weight: 600;
  }

  @media (max-width: 575.98px) {
    article > .profile {
      width: 145px !important;
      max-width: 45%;
      margin-top: 0;
    }

    .post-header {
      margin-bottom: 0.75rem;
    }

    .home-sections {
      clear: both;
      margin-top: 0;
      padding-top: 0.55rem;
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
  I am currently a research intern at <a href="https://pi.snu.ac.kr/" target="_blank" rel="noopener noreferrer">SNU PI Lab</a>, led by Prof. Youngjae Yu.
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

<div class="news">
  {% if site.news != blank %}
    {% assign news_size = site.news | size %}
    <div
      class="table-responsive"
      {% if page.announcements.scrollable and news_size > 3 %}
        style="max-height: 60vw"
      {% endif %}
    >
      <table class="table table-sm table-borderless">
        {% assign news = site.news | reverse %}
        {% assign news_limit = page.announcements.limit | default: news_size %}
        {% for item in news limit: news_limit %}
          <tr>
            <th scope="row" style="width: 20%">{{ item.date | date: '%b %Y' }}</th>
            <td>
              {% if item.inline %}
                {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
              {% else %}
                <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
              {% endif %}
            </td>
          </tr>
        {% endfor %}
      </table>
    </div>
  {% else %}
    <p>No news so far...</p>
  {% endif %}
</div>

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

    const splitTldr = (text) => {
      const cleanText = text
        .replace(/\s+/g, " ")
        .trim()
        .replace(/^TL;DR:\s*/i, "")
        .trim();
      const sentences = cleanText.match(/[^.!?]+[.!?]+(?:\s|$)|[^.!?]+$/g) || [cleanText];
      const preview = sentences[0].trim();
      return {
        preview,
        rest: cleanText.slice(preview.length).trim(),
      };
    };

    document.querySelectorAll(".publication-panel .links").forEach((links) => {
      const entry = links.closest("[id]");
      const abstractBlock = entry?.querySelector("div.abstract");
      const abstractButton = links.querySelector("a.abstract");

      abstractButton?.remove();

      if (entry && abstractBlock && !entry.querySelector(".publication-tldr")) {
        const { preview, rest } = splitTldr(abstractBlock.textContent);
        const tldr = document.createElement("div");
        const paragraph = document.createElement("p");
        const label = document.createElement("span");

        tldr.className = "publication-tldr";
        label.className = "publication-tldr-label";
        label.textContent = "TL;DR: ";

        paragraph.append(label, document.createTextNode(preview));

        if (rest) {
          const more = document.createElement("span");
          const toggle = document.createElement("button");

          more.className = "publication-tldr-more";
          more.hidden = true;
          more.textContent = ` ${rest}`;

          toggle.className = "publication-tldr-toggle";
          toggle.type = "button";
          toggle.setAttribute("aria-expanded", "false");
          toggle.textContent = "show more";
          toggle.addEventListener("click", () => {
            const expanded = toggle.getAttribute("aria-expanded") === "true";
            more.hidden = expanded;
            toggle.setAttribute("aria-expanded", String(!expanded));
            toggle.textContent = expanded ? "show more" : "show less";
          });

          paragraph.append(more, toggle);
        }

        tldr.appendChild(paragraph);
        links.after(tldr);
      }

      const preferredOrder = ["arXiv", "Website", "Bib"];
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
