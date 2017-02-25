---
layout: page
title:  "Archive"
permalink : "/archive/"
category: "archive"
---

{% for post in site.posts%}

  <div class="post postContent">
    <div class="postDate"><time datetime="{{ post.date | date_to_xmlschema }}" itemprop="datePublished">{{ post.date | date: "%b %-d, %Y" }}</time>
    </div>
    <div class="postTag">
      Tags: {{post.tag}}
    </div>
    <br>
    <div class="postTitle">
      <md-tooltip md-direction="top">by {{post.author}}</md-tooltip>
      <a class='postLink' href="{{site.url}}{{site.baseurl}}{{post.url}}">{{post.title}}</a>
    </div>
    <div class="postExt">
   {{ post.content | strip_html | truncatewords:40}}
    </div>
  </div>

  {% endfor %}



<div>


</div>
