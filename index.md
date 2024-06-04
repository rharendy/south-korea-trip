---
layout: default
title: Table of Contents
---
    <header>
        <p>Embark on an unforgettable journey through Seoul and Busan with our comprehensive guide tailored for travelers on a budget. Discover top attractions, cozy accommodations, and delectable culinary delights while navigating essential travel tips and cultural insights. From exploring iconic tourist spots and university campuses to stocking up on budget-friendly food options and mastering public transportation, this guide has everything you need for a memorable 4-day adventure. Stay connected, stay safe, and immerse yourself in the vibrant culture and rich history of these dynamic Korean cities.</p>
    </header>

<h1>Table of Contents</h1>

<ul>
{% for file in site.markdown_files %}
<li>
    <a href="{{ file.url | relative_url }}">{{ file.title | file.path }}</a>
</li>
{% endfor %}
</ul>
