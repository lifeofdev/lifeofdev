---
layout: categories
title: Bookmark
description: Bookmark
keywords: Bookmark
comments: false
menu: bookmark
permalink: /bookmark
---

<!-- <section class="container posts-content">
{% assign bookmarks = site.data.bookmarks %}
{% for bookmark in bookmarks %}
<h3>{{ bookmark | first }}</h3>
<ol class="posts-list" id="{{ bookmark[0] }}">
{% for post in bookmark.last %}
<li class="posts-list-item">
<span class="posts-list-meta">{{ post.date | date:"%Y-%m-%d" }}</span>
<a class="posts-list-name" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>
{% endfor %}
</section> -->
<!-- /section.content -->

<!-- ## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %} -->

{% for group in site.data.bookmarks %}
### {{ group.group }}

{% endfor %}
