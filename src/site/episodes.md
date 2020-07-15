---
title: Episodes
layout: layouts/base.njk
subtitle: This is the full archive of episodes. We have them sorted by season, but feel free to just find a movie you enjoy and start there.
---

<h3>Jump to a Season:</h3>
<ul class="podcasts">
	<li><a href="#problematic">Problematic Faves</a></li>
	<li><a href="#dumb">Our Dumb Decade</a></li>
	<li><a href="summer97">Summer of 1997</a></li>
	<li><a href="fears">Fears & Phobias</a></li>
	<li><a href="failsons">Failsons</a></li>
	<li><a href="bonus">Bonus</a></li>
</ul>
<br class="clear" />
<h2 id="problematic" class="season">Problematic Faves</h2>
We each pick a title that we still love even though, maybe we shouldn't?
<div class="flex-grid">
	{%- for page in collections.problematic -%}
	  <div class="episode">
	  	<a href="{{ page.url }}"><img src="/images/{{ page.data.image }}-thumb.jpg" alt="{{ page.data.title }}" /></a>
	  	<div>
		  	<h3><a href="{{ page.url }}">{{ page.data.title }}</a></h3>
		  	<p>{{ page.data.subtitle }}</p>
		    <span datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</span>
	  </div>
	 </div>
	{%- endfor -%}
</div>

<h2 id="dumb" class="season">Our Dumb Decade</h2>
It's time to look back at the way movies looked forward to the 2010s. 
<div class="flex-grid">
	{%- for page in collections.dumb -%}
	  <div class="episode">
	  	<a href="{{ page.url }}"><img src="/images/{{ page.data.image }}-thumb.jpg" alt="{{ page.data.title }}" /></a>
	  	<div>
		  	<h3><a href="{{ page.url }}">{{ page.data.title }}</a></h3>
		  	<p>{{ page.data.subtitle }}</p>
		    <span datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</span>
	  </div>
	 </div>
	{%- endfor -%}
</div>