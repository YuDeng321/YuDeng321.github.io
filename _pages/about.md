---
layout: research-home
permalink: /
title: "Yu Deng"
description: "Yu Deng works toward embodied robotic reasoning through explicit policy knowledge, robot learning, and grounded perception."
redirect_from:
  - /about/
  - /about.html
---

<section class="academic-section academic-about" id="about" aria-labelledby="about-title">
  <h1 id="about-title">About</h1>
  <div class="academic-about__layout">
    <div class="academic-about__text">
      <p>I am <strong>Yu Deng</strong>, a Ph.D. candidate in the <a href="https://www.aiml.informatik.tu-darmstadt.de/">AI/ML Lab at TU Darmstadt</a>, supervised by <a href="https://www.aiml.informatik.tu-darmstadt.de/people/kkersting">Prof. Dr. Kristian Kersting</a>. I am also affiliated with <a href="https://hessian.ai/">hessian.AI</a> and the <a href="https://www.fz-juelich.de/en/jsc/jupiter/jaif-jupiter-ai-factory">JUPITER AI Factory</a>.</p>
      <p>My long-term goal is <strong>embodied robotic reasoning</strong>: building robots that can form explicit, inspectable models of the physical world and their own behavior, test those models through interaction, and use what they learn to act more reliably in changing environments.</p>
      <p class="academic-links" id="contact"><a href="mailto:yu.deng@tu-darmstadt.de">Email</a><a href="https://scholar.google.com/citations?user=AiBmRA4AAAAJ">Google Scholar</a><a href="https://github.com/YuDeng321">GitHub</a></p>
    </div>
    <figure class="academic-about__portrait"><img src="/images/zaizai-avatar.jpg" alt="Zaizai, Yu Deng's cat" width="720" height="720"></figure>
  </div>
</section>

<section class="academic-section" id="publications" aria-labelledby="publications-title">
  <h2 id="publications-title">Publications</h2>
  <h3>2026</h3>
  <ul class="academic-papers">
    <li class="academic-paper" id="storm">
      <a class="academic-paper__image" href="https://arxiv.org/abs/2511.09771" aria-label="Read the STORM paper"><img src="/images/publications/storm.webp" alt="Object tracking example across a large camera viewpoint change" width="587" height="232" loading="lazy" decoding="async"></a>
      <div class="academic-paper__content">
        <h4>STORM: Segment, Track, and Object Re-Localization from a Single Image</h4>
        <p class="academic-paper__authors"><strong>Yu Deng*</strong>, Teng Cao*, Hikaru Shindo, Quentin Delfosse, Jiahong Xue, Kristian Kersting</p>
        <p class="academic-paper__meta"><span>ICML 2026</span><a href="https://arxiv.org/abs/2511.09771">Paper</a><a href="https://github.com/YuDeng321/STORM">Code</a></p>
        <p class="academic-paper__summary">Tracks 6D object pose from a reference image, detects drift, and re-localizes after occlusion or viewpoint changes.</p>
      </div>
    </li>
    <li class="academic-paper" id="robot-dift">
      <a class="academic-paper__image" href="https://arxiv.org/abs/2602.11934" aria-label="Read the Robot-DIFT paper"><img src="/images/publications/robot-dift.webp" alt="Robot arms performing four contact-sensitive manipulation tasks" width="745" height="500" loading="lazy" decoding="async"></a>
      <div class="academic-paper__content">
        <h4>Robot-DIFT: Correspondence-Sensitive Diffusion Features for Contact-Rich Robot Manipulation</h4>
        <p class="academic-paper__authors"><strong>Yu Deng*</strong>, Yufeng Jin*, Xiaogang Jia, Jiahong Xue, Gerhard Neumann, Georgia Chalvatzaki</p>
        <p class="academic-paper__meta"><span>CoRL 2026 (accepted)</span><a href="https://arxiv.org/abs/2602.11934">Paper</a></p>
        <p class="academic-paper__summary">Distills diffusion features into a fast visual backbone that preserves geometric correspondences needed for contact-rich control.</p>
      </div>
    </li>
    <li class="academic-paper" id="nautilus">
      <a class="academic-paper__image" href="https://arxiv.org/abs/2605.11665" aria-label="Read the Nautilus paper"><img src="/images/publications/nautilus.webp" alt="Nautilus connects robot policies, simulators, benchmarks, and robots through a shared harness" width="900" height="444" loading="lazy" decoding="async"></a>
      <div class="academic-paper__content">
        <h4>Nautilus: From One Prompt to Plug-and-Play Robot Learning</h4>
        <p class="academic-paper__authors">Yufeng Jin*, Jianfei Guo*, Xiaogang Jia, <strong>Yu Deng</strong>, Zechu Li, Han Liu, Weiran Liao, Vignesh Prasad, Mathias Franzius, Gerhard Neumann, Georgia Chalvatzaki</p>
        <p class="academic-paper__meta"><span>NeurIPS 2026 · Poster</span><a href="https://arxiv.org/abs/2605.11665">Paper</a></p>
        <p class="academic-paper__summary">Turns a single prompt into validated workflows for reproducing, evaluating, fine-tuning, and deploying robot learning methods.</p>
      </div>
    </li>
  </ul>
  <h3>Preprints</h3>
  <ul class="academic-papers">
    <li class="academic-paper" id="kintsugi">
      <a class="academic-paper__image" href="https://arxiv.org/abs/2605.09487" aria-label="Read the Kintsugi paper"><img src="/images/publications/kintsugi.webp" alt="Kintsugi turns failure evidence into verified edits to an executable knowledge base" width="900" height="365" loading="lazy" decoding="async"></a>
      <div class="academic-paper__content">
        <h4>Kintsugi: Learning Policies by Repairing Executable Knowledge Bases</h4>
        <p class="academic-paper__authors">Teng Cao*, <strong>Yu Deng*</strong>, Hikaru Shindo*, Quentin Delfosse, Lanxi Wen, Suli Wang, Jannis Blüml, Christopher Tauchmann, Kristian Kersting</p>
        <p class="academic-paper__meta"><span>arXiv 2026</span><a href="https://arxiv.org/abs/2605.09487">Paper</a></p>
        <p class="academic-paper__summary">Repairs explicit policy knowledge from rollout failures and admits each edit only after execution and regression checks.</p>
      </div>
    </li>
    <li class="academic-paper" id="behavioral-models">
      <a class="academic-paper__image" href="https://arxiv.org/abs/2606.07127" aria-label="Read the explicit behavioral models paper"><img src="/images/publications/behavioral-models.webp" alt="Adaptive questions and world-model probes train an explicit symbolic behavioral model" width="900" height="352" loading="lazy" decoding="async"></a>
      <div class="academic-paper__content">
        <h4>Learning Explicit Behavioral Models with Adaptive Questions and World-Model Probes</h4>
        <p class="academic-paper__authors">Hikaru Shindo, <strong>Yu Deng</strong>, Teng Cao, Quentin Delfosse, Christopher Tauchmann, Jannis Blüml, Gopika Sudhakaran, Kristian Kersting</p>
        <p class="academic-paper__meta"><span>arXiv 2026</span><a href="https://arxiv.org/abs/2606.07127">Paper</a></p>
        <p class="academic-paper__summary">Learns inspectable behavioral models through task feedback, adaptive questions, and executable world-model probes.</p>
      </div>
    </li>
    <li class="academic-paper" id="cognifold">
      <a class="academic-paper__image" href="https://arxiv.org/abs/2605.13438" aria-label="Read the CogniFold paper"><img src="/images/publications/cognifold.webp" alt="CogniFold organizes event streams into three interacting cognitive memory layers" width="900" height="357" loading="lazy" decoding="async"></a>
      <div class="academic-paper__content">
        <h4>CogniFold: Always-On Proactive Memory via Cognitive Folding</h4>
        <p class="academic-paper__authors">Suli Wang*, Yiqun Duan*, <strong>Yu Deng*</strong>, Rundong Zhao, Dai Shi, Minghua Deng, Chen Chen, Yiqi Wang, Xinliang Zhou</p>
        <p class="academic-paper__meta"><span>arXiv 2026</span><a href="https://arxiv.org/abs/2605.13438">Paper</a><a href="https://github.com/OpenUploading/CogniFold">Code</a></p>
        <p class="academic-paper__summary">Folds incoming events into evolving memory structures that can surface concepts and intentions for proactive agents.</p>
      </div>
    </li>
  </ul>
  <p class="academic-note">* Equal contribution.</p>
</section>

<section class="academic-section" id="education" aria-labelledby="education-title">
  <h2 id="education-title">Education</h2>
  <ul class="academic-education">
    <li><strong>Ph.D.</strong>, TU Darmstadt, since April 2026</li>
    <li><strong>M.Sc.</strong>, TU Darmstadt, October 2023 – February 2026</li>
  </ul>
</section>
