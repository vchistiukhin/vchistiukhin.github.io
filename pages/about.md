---
layout: page
title: About
permalink: /about
redirect_from:
  - /
  - /ab
weight: 1
timeline: about_timeline
---

{%include avatar.html%}

<br>Hi there! I am Vladimir Chistiukhin, Your Fellow QA engineer. 
<br>Having experience in enhancing quality assurance processes across multiple projects,<br> I like to go through every detail, see the full picture, test the most complicated solutions, and find tricky issues.<br><br> In the last few years, my primary focus has been on: 
 - creating comprehensive documentation that covers various scenarios.
 - engaging in the entire development process from planning to release.  
 - all-round testing for backend; iOS, Android, and web applications.
 - adopting the best practices to improve testing strategies.

Take a look at the <a href="/projects" class="grey-link">Projects</a> I have been involved in, or at my <a href="/timeline" class="grey-link">Timeline</a>.<br>
Let's stay in touch - connect with me on <a href="https://www.linkedin.com/in/vladimir-chistiukhin" class="grey-link">LinkedIn</a>, send me a message in <a href="https://telegram.me/kikirike" class="grey-link">Telegram</a>, or write me an <a href="mailto:vchistiukhin@gmail.com" class="grey-link">Email</a>.

<div class="row">
{% include about/skills.html title="QA Skills" source=site.data.qa-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>

<div class="buttons-container text-center">
  {% include elements/button.html link="/projects" text="Projects <i class='fas fa-arrow-right'></i> " %}
</div>