---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit jekyll-theme-simple-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
permalink: /index.html
header:
  image: /assets/img/home-header.jpg
tagline: > # this means to ignore newlines until "repository:"
  Author of The Extraordinary Lives of Ordinary People.
repository:
  is_project_page: false
  show_downloads: false
  ref: home
lang: en
---

Gauri Jhangiani is a young author with a zest for both writing and life. When she's not writing, she enjoys reading, binge-watching TV shows and spending many hours on Tumblr. The Extraordinary Lives of Ordinary People is her first book. 
<h1>Latest Articles</h1>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="articles" max_posts=100 max_post_tags=3 %}

---