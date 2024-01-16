<!-- ---
layout: archive
permalink: /year-archive/
title: "Blog posts"
author_profile: true
redirect_from:
  - /wordpress/blog-posts/
---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %} -->
\


# Awards & Achievements

- **2016:** Graduated at the Top of my institution with a remarkable 78.93%.
  
- **2021:** Achieved All-India-Rank 1 in the C-CAT (Centre for Development of Advanced Computing) entrance exam among 90,000 candidates.

- **2015:** Secured 1st place in CodeStorm - Competitive Programming.

- **2021:** Clinched the 1st prize in Paper Presentation for "Flying Rubicks with self-assembly with M-Blocks."

- **2021:** Bagged another 1st prize in Paper Presentation for "Flying Rubicks with self-assembly with M-Blocks."

- **2015:** Achieved 1st prize in the Google Challenge by completing all challenging tasks with the fastest time and the best score.

- **2016:** Emerged victorious with the 1st prize in Google Junk, showcasing exceptional speed and skill in completing challenging tasks.

- **2016:** Captained a team of 6 to secure the 2nd prize in Boc Cricket, triumphing over 30 competing teams.

- **2016:** Recognized as a Finalist in Aptitude Cracker.

- **2016:** Finalist in Poster Presentation on "Women Empowerment."


