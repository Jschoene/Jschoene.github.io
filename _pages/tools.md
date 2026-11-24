---
layout: page
permalink: /tools/
title: Tools
description: Research tools and AI chatbots from the E.T Lab and collaborators.
nav: true
nav_order: 6
---

<script>
document.addEventListener('DOMContentLoaded', function() {
  var b = document.querySelector('.navbar-brand');
  if (b) { var s = b.querySelector('.font-weight-bold'); if (s) s.style.fontWeight = '400'; b.lastChild.textContent = ''; var bold = document.createElement('span'); bold.style.fontWeight = '700'; bold.textContent = ' Sch\u00F6ne'; b.appendChild(bold); }
});
</script>

## Well-Being Chatbots

These chatbots were developed as part of the [AI and Emotional Well-Being](https://ai4pb.stanford.edu/project-categories/ai-and-emotional-well-being) initiative at the Stanford AI for Public Benefit Lab (with [Robb Willer](https://sociology.stanford.edu/people/robb-willer) and [Johannes Eichstaedt](https://profiles.stanford.edu/eich)). Each chatbot guides users through a brief, structured conversation grounded in well-being research. In a preregistered experiment (N = 2,922), these dialogues produced short-term improvements on several well-being outcomes. See [Schöne et al. (under review)](/publications/) for details.

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1.5rem; margin: 2rem 0;">

  <div style="text-align: center; padding: 1.5rem; border: 1px solid #ddd; border-radius: 10px;">
    <i class="fas fa-compass" style="font-size: 2.5rem; color: #1B2A4A; margin-bottom: 0.75rem;"></i>
    <h4 style="margin: 0.5rem 0 0.25rem;">Hero's Journey</h4>
    <p style="font-size: 0.9rem; color: #555;">Reframe challenges and strengths by viewing your life as a story and identifying actions aligned with your values.</p>
    <a href="https://herobot.aiwellbeing.org/" target="_blank" style="font-weight: 600;">Try it <i class="fas fa-arrow-right"></i></a>
  </div>

  <div style="text-align: center; padding: 1.5rem; border: 1px solid #ddd; border-radius: 10px;">
    <i class="fas fa-lightbulb" style="font-size: 2.5rem; color: #1B2A4A; margin-bottom: 0.75rem;"></i>
    <h4 style="margin: 0.5rem 0 0.25rem;">Meaning</h4>
    <p style="font-size: 0.9rem; color: #555;">Reflect on what gives you purpose -- the people, roles, and commitments that matter most.</p>
    <a href="https://meaningbot.aiwellbeing.org/" target="_blank" style="font-weight: 600;">Try it <i class="fas fa-arrow-right"></i></a>
  </div>

  <div style="text-align: center; padding: 1.5rem; border: 1px solid #ddd; border-radius: 10px;">
    <i class="fas fa-heart" style="font-size: 2.5rem; color: #1B2A4A; margin-bottom: 0.75rem;"></i>
    <h4 style="margin: 0.5rem 0 0.25rem;">Gratitude</h4>
    <p style="font-size: 0.9rem; color: #555;">Express gratitude to a specific person and notice how others contribute to your life.</p>
    <a href="https://gratitudebot.aiwellbeing.org/" target="_blank" style="font-weight: 600;">Try it <i class="fas fa-arrow-right"></i></a>
  </div>

  <div style="text-align: center; padding: 1.5rem; border: 1px solid #ddd; border-radius: 10px;">
    <i class="fas fa-sun" style="font-size: 2.5rem; color: #1B2A4A; margin-bottom: 0.75rem;"></i>
    <h4 style="margin: 0.5rem 0 0.25rem;">Savoring</h4>
    <p style="font-size: 0.9rem; color: #555;">Slow down and revisit a positive moment in detail -- its sensations, thoughts, and meaning.</p>
    <a href="https://savoringbot.aiwellbeing.org/" target="_blank" style="font-weight: 600;">Try it <i class="fas fa-arrow-right"></i></a>
  </div>

</div>

<p style="font-size: 0.8rem; color: #888; margin-top: 0.5rem;"><em>These demos are educational research prototypes and do not provide medical or mental health advice. They are not a substitute for professional diagnosis, treatment, or therapy.</em></p>

---

## Coming Soon

### Social Media Well-Being Filter

A browser-based tool that lets users filter negative content from their social media feeds in real time. Building on our research showing that exposure to algorithmically amplified negativity harms well-being, this tool will give people control over what emotional content they encounter online. Details and a public release to follow.
