---
---

Welcome to the Beytah Hoard! This is a small, curated directory of anything
prerelease, prototype, or otherwise hidden in any sort of media (we're mostly
interested in video games though). And you're welcome to [pitch in](https://github.com/beytahhoard/beytahhoard.github.io/pulls) and/or
[study](https://github.com/beytahhoard/beytahhoard.github.io) how we do things around here.

<div class="container">
	<div class="column">
	<h2>Beytah</h2>
	<p>For prerelease material, leaked or otherwise.</p>
	<ul>
	{% for post in site.beytah %}
		<li><a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
	</ul>
	</div>
	<div class="column">
	<h2>Secrets</h2>
	<p>For things already found in final releases, but <i>generally</i> inaccessible or leftovers.</p>
	<ul>
	{% for post in site.secrets %}
		<li><a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
	</ul>
	</div>
</div>
