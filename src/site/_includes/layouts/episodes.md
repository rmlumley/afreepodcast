---
layout: layouts/base.njk
pageClass: episodes
templateEngineOverride: njk, md
---

<p class="date">
  <time datetime="{{ date }}">{{ date | dateDisplay }}</time>
</p>
<main>
  {{ content | safe }}
  <h3>Other episodes from this season:</h3>
  <ul class="podcasts">
  {%- for page in collections.problematic -%}
    <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
  {%- endfor -%}
  </ul>
  <br class="clear" />
  <div class="footnote flex-grid">
  	<div>
  		<h3>About this podcast</h3>
  		<p><a href="/">A Free Podcast</a> is a podcast by The Midnight Boys that looks at the big themes in movies. Like why spiders are scary and how cool 1997 was.</p>
  	</div>
  	<div>
    	<h3>Discuss this episode</h3>
		<p>Join other listeners of A Free Podcast and join our Facebook group, <a href="http://afreepodcast.com/freeloaders">Freeloaders</a>, to discuss this episode.</p>
	</div>
	<div>
		<h3>Support this nonsense</h3> 
		<p><a href="https://www.patreon.com/themidnightboys">Become a patreon</a> and get access to exclusive content.</p>
	</div>
  </div>
</main>
