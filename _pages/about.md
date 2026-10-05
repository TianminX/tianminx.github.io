---
layout: about
title: Home
permalink: /

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <nav class="profile-links" aria-label="Professional profiles">
      <a href="/assets/pdf/Tianmin_Xie_CV.pdf" target="_blank"><i class="fa-solid fa-file-lines"></i><span>CV</span></a>
      <a href="https://scholar.google.com/citations?user=jz9CqnoAAAAJ&hl=en" target="_blank"><i class="ai ai-google-scholar"></i><span>Google Scholar</span></a>
      <a href="mailto:Tianmin.Xie@marshall.usc.edu"><i class="fa-solid fa-envelope"></i><span>Email</span></a>
      <a href="https://github.com/TianminX" target="_blank"><i class="fa-brands fa-github"></i><span>GitHub</span></a>
    </nav>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items

latest_posts:
  enabled: false
---

<style>
  .post article {
    font-size: 1.06rem;
    line-height: 1.72;
  }

  @media (min-width: 768px) {
    .profile.float-left {
      width: 24%;
      max-width: 220px;
      margin-right: 2rem;
    }

    /* keep all text in the column beside the photo instead of wrapping under it */
    .post article > .clearfix {
      display: flow-root;
    }
  }

  .profile img {
    aspect-ratio: 4 / 5;
    object-fit: cover;
    object-position: 50% 30%;
    border-radius: 3px !important;
    box-shadow: 0 10px 28px rgba(29, 47, 48, 0.12);
  }

  .profile-links {
    display: grid;
    gap: 0.42rem;
    margin-top: 0.9rem;
    font-size: 0.98rem;
  }

  .profile-links a {
    display: flex;
    align-items: center;
    gap: 0.55rem;
    color: var(--global-theme-color);
    text-decoration: none;
  }

  .profile-links a:hover,
  .profile-links a:focus-visible {
    color: var(--global-hover-color);
    text-decoration: underline;
    text-underline-offset: 0.2em;
  }

  .profile-links i {
    width: 1.1rem;
    text-align: center;
  }

  .post article > hr {
    clear: both;
    margin: 2rem 0 1.35rem;
  }

  .post article h3 {
    margin-bottom: 0.75rem;
    font-size: 1.35rem;
  }

  .research-keywords {
    margin-top: 1rem;
    color: var(--global-text-color-light);
    letter-spacing: 0.01em;
  }

  @media (max-width: 767.98px) {
    .post article {
      font-size: 0.94rem;
      line-height: 1.62;
    }

    .profile.float-left {
      float: none !important;
      clear: both;
      display: grid;
      grid-template-columns: 144px minmax(0, 1fr);
      align-items: center;
      column-gap: 1rem;
      width: 100%;
      max-width: none;
      margin: 0 0 1.5rem;
    }

    .profile figure {
      width: 144px;
      margin: 0;
    }

    .profile img {
      width: 144px;
      max-width: 144px;
      margin: 0;
    }

    .profile .more-info {
      width: 100%;
      margin: 0;
    }

    .profile-links {
      grid-template-columns: 1fr;
      gap: 0.12rem;
      margin-top: 0;
      font-size: 0.82rem;
    }

    .profile-links a {
      min-height: 1.65rem;
      gap: 0.45rem;
    }

    .post article > p:first-of-type {
      clear: both;
    }

    .post article h3 {
      font-size: 1.15rem;
    }
  }
</style>

Welcome to my homepage! I am a Ph.D. student in Statistics in the [Department of Data Sciences and Operations](https://www.marshall.usc.edu/departments/data-sciences-and-operations) at the [USC Marshall School of Business](https://www.marshall.usc.edu/), where I am advised by Professor [Matteo Sesia](https://msesia.github.io/).

Before coming to USC, I studied mathematics at the [University of Cambridge](https://www.cam.ac.uk/), where I received my bachelor's degree and Master of Mathematics (Part III).

---

### Research Interests

My research develops statistical methods for reliable uncertainty quantification in machine learning, with a focus on conformal inference. Recent work studies prediction sets for classification with rare and previously unseen classes, and joint confidence regions for matrix completion in group recommender systems.

<p class="research-keywords"><strong>Keywords:</strong> Conformal inference &nbsp;&middot;&nbsp; Uncertainty quantification &nbsp;&middot;&nbsp; Machine learning &nbsp;&middot;&nbsp; Recommender systems</p>
