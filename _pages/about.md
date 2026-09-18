---
layout: about
title: about
permalink: /
subtitle: M.S.E. Robotics @ University of Pennsylvania

profile:
  align: right
  image: IMG_2404.jpg
  image_circular: false
  more_info:

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<div class="intro-copy" markdown="1">

I am an M.S.E. student in Robotics at the University of Pennsylvania, where I am working with [Prof. Nadia Figueroa](https://nbfigueroa.github.io/) in the [Figueroa Robotics Lab](https://figueroa.seas.upenn.edu/), part of the [GRASP Laboratory](https://www.grasp.upenn.edu/). Prior to Penn, I received my B.E. in Artificial Intelligence from Tongji University.

My long-term goal is to build robots that can work alongside people in everyday human environments. My research focuses on **robot learning, imitation learning, and motion planning**, with an emphasis on adapting learned behaviors to new constraints and changing conditions.

</div>

<style>
.profile { width: 33.333% !important; }
.profile img { width: 100%; height: auto; object-fit: contain; }
.intro-copy {
  width: 61%;
  min-height: 28.1rem;
  padding: 1rem 1.15rem;
  border: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.intro-copy p { font-size: 1.04rem; line-height: 1.75; }
.intro-copy p:last-child { margin-bottom: 0; }
@media (max-width: 576px) {
  .profile { width: 100% !important; }
  .intro-copy { width: 100%; min-height: auto; margin-top: 1rem; }
  .intro-copy p { font-size: 1rem; line-height: 1.6; }
}
.selected-work-home { clear: both; padding-top: 1.4rem; }
.selected-work-home h2 { font-size: 1.25rem; margin-bottom: 0.25rem; }
.selected-work-home .section-rule { border-top: 1px solid var(--global-divider-color); margin-bottom: 0.35rem; }
.selected-work-home .work-item { display: grid; grid-template-columns: 38% minmax(0, 1fr); gap: 1.4rem; align-items: start; padding: 1.15rem 0; border-bottom: 1px solid var(--global-divider-color); }
.selected-work-home .work-title { font-size: 0.98rem; font-weight: 650; line-height: 1.35; margin-bottom: 0.12rem; }
.selected-work-home .work-meta { color: var(--global-text-color-light); font-size: 0.78rem; line-height: 1.45; margin-bottom: 0.12rem; }
.selected-work-home .work-desc { font-size: 0.84rem; line-height: 1.5; margin: 0; }
.selected-work-home .work-figure { display: block; margin: 0; border: 1px solid var(--global-divider-color); border-radius: 0; overflow: hidden; background: #fff; }
.selected-work-home .work-figure img { display: block; width: 100%; height: auto; object-fit: contain; aspect-ratio: 1910 / 844; }
.selected-work-home .work-media, .selected-work-home .work-copy { min-width: 0; }
@media (max-width: 575px) {
  .selected-work-home .work-item { grid-template-columns: minmax(0, 1fr); gap: .75rem; }
  .selected-work-home .work-media { width: 100%; max-width: 340px; }
}
</style>

<section class="selected-work-home">
  <h2>selected work</h2>
  <div class="section-rule"></div>

  <div class="work-item">
    <div class="work-media">
      <div class="work-figure">
      <img src="{{ '/assets/img/replanning-compact.webp' | relative_url }}" alt="RoboMimic method comparisons under no-jitter and boundary-box constraints at 0, 5 and 10 seconds" width="1910" height="844" loading="lazy" decoding="async">
    </div>
    </div>
    <div class="work-copy">
      <div class="work-title">Bilinear Latent Dynamics for Consequence-Preserving Replanning</div>
    <div class="work-meta">First author · Accepted to IROS 2026 Workshop · Figueroa Robotics Lab, University of Pennsylvania</div>
    <p class="work-desc">Replanning for frozen generative imitation policies under unseen geometric, smoothness, and dynamics constraints.</p>
    </div>
  </div>

  <div class="work-item">
    <div class="work-media">
      <div class="work-figure">
      <img src="{{ '/assets/img/moodtune-compact.webp' | relative_url }}" alt="Music recommendation pipeline and system modules, application interface, two- and five-cluster plots and cluster evaluation" width="1910" height="844" loading="lazy" decoding="async">
    </div>
    </div>
    <div class="work-copy">
      <div class="work-title">MoodTune: AI-Driven Music Therapy Platform</div>
    <div class="work-meta">Co-first author · APIT 2025 · Best Presentation Award</div>
    <p class="work-desc">Multimodal emotion recognition and personalized music recommendation for therapeutic applications.</p>
    </div>
  </div>

  <div class="work-item">
    <div class="work-media">
      <div class="work-figure">
      <img src="{{ '/assets/img/eeg-fatigue-compact.webp' | relative_url }}" alt="Original BrainBeats device, acquisition hardware, live EEG and English system workflow" width="1910" height="844" loading="lazy" decoding="async">
    </div>
    </div>
    <div class="work-copy">
      <div class="work-title">Cross-Subject EEG Fatigue Recognition</div>
    <div class="work-meta">SAIC Volkswagen · Patent application</div>
    <p class="work-desc">EEG-Conformer and cross-subject evaluation for robust driver-fatigue decoding.</p>
    </div>
  </div>

</section>
