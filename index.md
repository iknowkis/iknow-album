---
layout: home
title: Lens by HTML5 UP
---

<!-- Thumbnail -->
<section id="thumbnails">{% for photo in site.photos %}
	<article>
		<a class="thumbnail" href="{{ photo.image }}" data-position="left center"><img src="{{ photo.thumbnail }}" alt="" /></a>
		<h2>{{ photo.title }}</h2>
		<p>{{ photo.caption }}</p>
	</article>
{% endfor %}
				<article>
				<a class="thumbnail" href="assets\images\fulls\13.jpg">
					<img src="assets\images\thumbs\13.jpg" alt="" />
				</a>
				<h2>Title</h2>
				<p>Description.</p>
			</article>
</section>
