---
layout: archive
title: "About Me"
permalink: /aboutme/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .about-page {
    --about-accent: var(--global-link-color);
    --about-border: var(--global-border-color);
    --about-muted: var(--global-text-color-light);
  }

  .about-page section {
    margin-bottom: 3rem;
  }

  .about-page h2 {
    margin: 0 0 1.15rem;
    padding: 0;
    border: 0;
    font-size: 1.3rem;
    line-height: 1.25;
    letter-spacing: -0.015em;
  }

  .about-timeline {
    position: relative;
    margin-left: 0.35rem;
    padding-left: 1.55rem;
    border-left: 1px solid var(--about-border);
  }

  .about-item {
    position: relative;
    margin-bottom: 0.75rem;
    padding-left: 0.3rem;
  }

  .about-item:last-child {
    margin-bottom: 0;
  }

  .about-item::before {
    content: "";
    position: absolute;
    top: 1rem;
    left: -1.91rem;
    width: 7px;
    height: 7px;
    border: 2px solid var(--global-bg-color);
    border-radius: 50%;
    background: var(--about-accent);
    box-shadow: 0 0 0 1px var(--about-accent);
  }

  .about-card {
    padding: 0.9rem 1rem;
    border: 1px solid var(--about-border);
    border-radius: 8px;
    background: var(--global-bg-color);
  }

  .about-card__title {
    margin: 0 0 0.3rem;
    font-size: 0.94rem;
    font-weight: 700;
    line-height: 1.4;
  }

  .about-card__meta {
    margin: 0 0 0.45rem;
    color: var(--about-accent);
    font-family: $sans-serif;
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0.045em;
    text-transform: uppercase;
  }

  .about-card__text {
    margin: 0;
    font-size: 0.86rem;
    line-height: 1.62;
  }

  .about-card__text + .about-card__text {
    margin-top: 0.35rem;
  }

  @media (max-width: 600px) {
    .about-timeline {
      margin-left: 0.2rem;
      padding-left: 1.25rem;
    }

    .about-item::before {
      left: -1.61rem;
    }
  }
</style>

<div class="about-page">

  <section>
    <h2>Education</h2>
    <div class="about-timeline">

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">Ongoing</p>
          <p class="about-card__title">PhD in English Language Teaching</p>
          <p class="about-card__text">Middle East Technical University, Faculty of Education, Department of Foreign Language Education, Ankara, TURKEY</p>
        </div>
      </article>

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__title">Master of Arts in English Language Teaching</p>
          <p class="about-card__text">Anadolu University, Faculty of Education, Department of Foreign Language Education, Eskişehir, TURKEY</p>
          <p class="about-card__text">Thesis Title: <var>“Designing and Implementing a Corpus-Based Language Teaching (CBLT) Training Program in a Pre-service EFL Teacher Education Context”,</var> Supervisor: Assoc. Prof. Dr. S. İpek Kuru Gönen</p>
        </div>
      </article>

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__title">Bachelor of Arts in English Language Teaching</p>
          <p class="about-card__text">Anadolu University, Faculty of Education, Department of Foreign Language Education, Eskişehir, TURKEY</p>
        </div>
      </article>

    </div>
  </section>

  <section>
    <h2>Work Experience</h2>
    <div class="about-timeline">

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">2022–to date</p>
          <p class="about-card__title">Research/Teaching Assistant</p>
          <p class="about-card__text">Middle East Technical University, Faculty of Education, Department of Foreign Language Education, Ankara, TURKEY</p>
        </div>
      </article>

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">2019–2022</p>
          <p class="about-card__title">English Language Instructor/K12 Teacher</p>
          <p class="about-card__text">Language School & Private Colleges, Eskişehir, TURKEY</p>
        </div>
      </article>

    </div>
  </section>

  <section>
    <h2>Exchange Experience</h2>
    <div class="about-timeline">

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">2018–2019</p>
          <p class="about-card__title">Erasmus Exchange</p>
          <p class="about-card__text">Bachelor of Arts - BA, English Language Teaching, 1 semester in Uniwersytet im. Adama Mickiewicza w Poznaniu, Poznań, POLAND</p>
        </div>
      </article>

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">2017</p>
          <p class="about-card__title">Erasmus+ Exchange</p>
          <p class="about-card__text">Elektrotehnička i prometna škola Osijek, Osijek, CROATIA</p>
        </div>
      </article>

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">2015</p>
          <p class="about-card__title">Erasmus+ Exchange</p>
          <p class="about-card__text">Liceum Ogólnoksztatcace im. Adama Mickiewicza w Opolu Lubelskim, Lublin, POLAND</p>
        </div>
      </article>

    </div>
  </section>

  <section>
    <h2>Volunteer Experience</h2>
    <div class="about-timeline">

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">2019–to date</p>
          <p class="about-card__title">Bilim Kahramanları Derneği</p>
          <p class="about-card__text">FIRST Lego League (FLL) Tournament Volunteer & Robot Games Referee</p>
        </div>
      </article>

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">2018–2022</p>
          <p class="about-card__title">Educational Volunteers Foundation of Turkey (TEGV)</p>
          <p class="about-card__text">English and Turkish Activity Volunteer</p>
        </div>
      </article>

      <article class="about-item">
        <div class="about-card">
          <p class="about-card__meta">2019–2022</p>
          <p class="about-card__title">Dorlion Search & Rescue Team (DAK)</p>
          <p class="about-card__text">Search & Rescue Team Member</p>
        </div>
      </article>

    </div>
  </section>

</div>

<!-- Floating Back to Top Button -->
<style>
#back-to-top {
  position: fixed;
  bottom: 30px;
  right: 30px;
  background-color: #555;
  color: white;
  border-radius: 50%;
  width: 45px;
  height: 45px;
  text-align: center;
  font-size: 24px;
  line-height: 45px;
  z-index: 999;
  text-decoration: none;
  box-shadow: 0 2px 5px rgba(0,0,0,0.3);
  transition: background-color 0.3s ease;
}
#back-to-top:hover {
  background-color: #333;
}

footer .sitemap {
  display: none !important;
}
</style>
<a href="#" id="back-to-top" onclick="window.scrollTo({top: 0, behavior: 'smooth'}); return false;">↑</a>
