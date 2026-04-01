---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- ============================================================ -->
<!-- EASY EDIT: Replace placeholder entries with your own.        -->
<!-- Each section uses standard Markdown lists/headers.           -->
<!-- You can also link to a PDF: [Download CV](../files/cv.pdf)   -->
<!-- ============================================================ -->

[Download PDF version](../files/cv.pdf){: .btn .btn--primary}

---

## Education

- **Ph.D.**, [Field], [University], [Year expected/awarded]
- **M.Sc.**, [Field], [University], [Year]
- **B.Sc.**, [Field], [University], [Year]

---

## Positions

- **[Year–present]** [Title], [Institution], [Department/Lab]
- **[Year–Year]** [Title], [Institution]

---

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

## Awards & Fellowships

<!-- List awards, scholarships, fellowships, etc. -->

- **[Year]** — [Award name], [Granting institution]
- **[Year]** — [Award name], [Granting institution]

---

## Teaching

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

## Talks & Presentations

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

---

## Skills & Tools

- **Languages:** [e.g., Python, R, Julia, MATLAB]
- **Frameworks:** [e.g., PyTorch, TensorFlow, Stan]
- **Other:** [e.g., LaTeX, Git, SQL]

---

## Service

- **[Year–present]** Reviewer for [Journal/Conference]
- **[Year]** [Committee or service role], [Institution/Organization]
