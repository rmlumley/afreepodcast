---
title: Episodes
layout: layouts/base.njk
subtitle: This is the full archive of episodes. We have them sorted by season, but feel free to just find a movie you enjoy and start there.
---

<h3>Jump to a Season:</h3>
<ul class="podcasts">
	<li><a href="#minnesota">Made in Minnesota</a></li>
	<li><a href="#buddy">Buddy Cops</a></li>
	<li><a href="#midlife">Midlife Crisis</a></li>
	<li><a href="#dealer">Dealer's Choice</a></li>
	<li><a href="#asseenontv">As Seen on TV</a></li>
	<li><a href="#twilight">Another Dimension</a></li>
	<li><a href="#work">Work Sucks</a></li>
	<li><a href="#online">Goin' Online</a></li>
	<li><a href="#wrestling">Wrestling with Hollywood</a></li>
	<li><a href="#dad">How to Be a Dad</a></li>
	<li><a href="#attack">When Movies Attack</a></li>
	<li><a href="#bond">Bond by B.A.H.N.D</a></li>
	<li><a href="#rock">Rock Docs</a></li>
	<li><a href="#monster">Monster Rehash</a></li>
	<li><a href="#erotic">Erotic Thrillers</a></li>
	<li><a href="#problematic">Problematic Faves</a></li>
	<li><a href="#dumb">Our Dumb Decade</a></li>
	<li><a href="#summer1997">Summer of 1997</a></li>
	<li><a href="#fears">Fears & Phobias</a></li>
	<li><a href="#failsons">Failsons</a></li>
	<li><a href="#listener">Listener Request</a></li>
	<li><a href="#bonus">Bonus</a></li>
	<li><a href="#patreon">Patreon</a></li>
</ul>
<br class="clear" />
<h2 id="minnesota" class="season">Made in Minnesota</h2>
We go back to Duff's home state and examine movies that were made in Minnesota.
<div class="flex-grid">
	{%- for page in collections.minnesota -%}
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
<h2 id="buddy" class="season">Buddy Cops</h2>
We use our B.U.D. system to decide which Buddy Cop movie is the best.
<div class="flex-grid">
	{%- for page in collections.buddy -%}
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
<h2 id="midlife" class="season">Midlife Crisis</h2>
We look at films that explore characters navigating the challenges of middle age. A subject we know nothing about, obviously.
<div class="flex-grid">
	{%- for page in collections.midlife -%}
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
<h2 id="dealer" class="season">Dealer's Choice</h2>
We pick a movie that the other two hosts have yet to see. 
<div class="flex-grid">
	{%- for page in collections.dealer -%}
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
<h2 id="asseenontv" class="season">As Seen on TV</h2>
From the days when broadcast television cranked out movies of their own.
<div class="flex-grid">
	{%- for page in collections.asseenontv -%}
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
<h2 id="twilight" class="season">Another Dimension</h2>
The Twilight Zone was one of the most influential shows in TV history. We look at the directors who moved to film either before or after their Twilight Zone work.
<div class="flex-grid">
	{%- for page in collections.twilight -%}
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
<h2 id="work" class="season">Work Sucks</h2>
We examine the pitfalls of work and ask, what are we doing?
<div class="flex-grid">
	{%- for page in collections.work -%}
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
<h2 id="online" class="season">Goin' Online</h2>
Fire up your dial up modem and join us as we look at movies that tackled the world wide web.
<div class="flex-grid">
	{%- for page in collections.online -%}
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
<h2 id="wrestling" class="season">Wrestling with Hollywood</h2>
In the past 40 years, various professional wrestlers have made the leap to Hollywood. We look at a movie from each and talk about their careers in and out of the ring.
<div class="flex-grid">
	{%- for page in collections.wrestling -%}
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
<h2 id="dad" class="season">How to Be a Dad</h2>
The Midnight Boys are here with your cinematic guide on fatherhood.
<div class="flex-grid">
	{%- for page in collections.dad -%}
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
<h2 id="attack" class="season">When Movies Attack</h2>
Sometimes movie productions are so troubled that they overshadow the actual films being made. This season is on WHEN MOVIES ATTACK!
<div class="flex-grid">
	{%- for page in collections.attack -%}
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
<h2 id="listener" class="season">Listener Request</h2>
Fans who sign up on our <a href="https://patreon.com/themidnightboys">Patreon</a> can pay for an individual episode that will release on A Free Podcast.
<div class="flex-grid">
	{%- for page in collections.listener | reverse -%}
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