---
title: Episodes
layout: layouts/base.njk
subtitle: This is the full archive of episodes. We have them sorted by season, but feel free to just find a movie you enjoy and start there.
---

<h3>Jump to a Season:</h3>
<ul class="podcasts">
	<li><a href="#bond">Bond by B.A.H.N.D</a></li>
	<li><a href="#rock">Rock Docs</a></li>
	<li><a href="#monster">Monster Rehash</a></li>
	<li><a href="#erotic">Erotic Thrillers</a></li>
	<li><a href="#problematic">Problematic Faves</a></li>
	<li><a href="#dumb">Our Dumb Decade</a></li>
	<li><a href="#summer1997">Summer of 1997</a></li>
	<li><a href="#fears">Fears & Phobias</a></li>
	<li><a href="#failsons">Failsons</a></li>
	<li><a href="#bonus">Bonus</a></li>
	<li><a href="#patreon">Patreon</a></li>
</ul>
<br class="clear" />
<h2 id="bond" class="season">Bond by B.A.H.N.D</h2>
The Midnight Boys go through a cultural blindspot for them. We pick a movie from each Bond actor and determine their B.A.H.N.D rating.
<div class="flex-grid">
	{%- for page in collections.bond -%}
	  <div class="episode {{ page.data.paid }}">
	  	<a href="{{ page.url }}"><img src="/images/{{ page.data.image }}-thumb.jpg" alt="{{ page.data.title }}" /></a>
	  	<div>
		  	<h3><a href="{{ page.url }}">{{ page.data.title }}</a></h3>
		  	<p>{{ page.data.subtitle }}</p>
		    <span datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</span>
	  </div>
	 </div>
	{%- endfor -%}
</div>
<h2 id="rock" class="season">Rock Docs</h2>
Our season on Rock Docs covers some notable music documentaries to help fill the live performance void in our lives.
<div class="flex-grid">
	{%- for page in collections.rock -%}
	  <div class="episode {{ page.data.paid }}">
	  	<a href="{{ page.url }}"><img src="/images/{{ page.data.image }}-thumb.jpg" alt="{{ page.data.title }}" /></a>
	  	<div>
		  	<h3><a href="{{ page.url }}">{{ page.data.title }}</a></h3>
		  	<p>{{ page.data.subtitle }}</p>
		    <span datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</span>
	  </div>
	 </div>
	{%- endfor -%}
</div>
<h2 id="monster" class="season">Monster Rehash</h2>
Throughout the 1990s, a number of Universal Picture's classic monsters were re-imagined. The quality of results were varied.
<div class="flex-grid">
	{%- for page in collections.monster -%}
	  <div class="episode {{ page.data.paid }}">
	  	<a href="{{ page.url }}"><img src="/images/{{ page.data.image }}-thumb.jpg" alt="{{ page.data.title }}" /></a>
	  	<div>
		  	<h3><a href="{{ page.url }}">{{ page.data.title }}</a></h3>
		  	<p>{{ page.data.subtitle }}</p>
		    <span datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</span>
	  </div>
	 </div>
	{%- endfor -%}
</div>
<h2 id="erotic" class="season">Erotic Thrillers</h2>
For 15 years this subgenre was a force at the Box Office and dominated video rentals.
<div class="flex-grid">
	{%- for page in collections.erotic -%}
	  <div class="episode {{ page.data.paid }}">
	  	<a href="{{ page.url }}"><img src="/images/{{ page.data.image }}-thumb.jpg" alt="{{ page.data.title }}" /></a>
	  	<div>
		  	<h3><a href="{{ page.url }}">{{ page.data.title }}</a></h3>
		  	<p>{{ page.data.subtitle }}</p>
		    <span datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</span>
	  </div>
	 </div>
	{%- endfor -%}
</div>
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
<h2 id="summer1997" class="season">Summer of 1997</h2>
Remember the movies from the summer of 1997? Well, we do.
<div class="flex-grid">
	{%- for page in collections.summer1997 -%}
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
<h2 id="fears" class="season">Fears & Phobias</h2>
We discuss movies that explore common fears & phobias.<div class="flex-grid">
	{%- for page in collections.fears -%}
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
<h2 id="failsons" class="season">Failsons</h2>
Let's talk about failsons. These are the boys born on 3rd base but still unable to get home.<div class="flex-grid">
	{%- for page in collections.failsons -%}
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
<h2 id="bonus" class="season">Bonus</h2>
Various one-off episodes we have made that don't really fit into any of the above seasons.
<div class="flex-grid">
	{%- for page in collections.bonus | reverse -%}
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
<h2 id="patreon" class="season">Patreon</h2>
This is available on our <a href="https://patreon.com/themidnightboys/">Patreon feed</a>. You can unlock all of our patreon episodes for $2.
<div class="flex-grid">
	{%- for page in collections.patreon | reverse -%}
	  <div class="episode {{ page.data.paid }}">
	  	<a href="{{ page.url }}"><img src="/images/{{ page.data.image }}-thumb.jpg" alt="{{ page.data.title }}" /></a>
	  	<div>
		  	<h3><a href="{{ page.url }}">{{ page.data.title }}</a></h3>
		  	<p>{{ page.data.subtitle }}</p>
		    <span datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</span>
	  </div>
	 </div>
	{%- endfor -%}
</div>