---
layout: page
title: About
description: 从来如此，便对吗？
keywords: Mf
comments: true
menu: 关于
permalink: /about/
---
生活在一定程度上就像游戏故事，只有做足了前置条件，那么剧情才会触发，或者说，努力到一定程度，该来的就会来了。


愿中国青年都摆脱冷气，只是向上走，不必听自暴自弃者流的话。
能做事的做事，能发声的发声。
有一分热，发一分光，就令萤火一般，也可以在黑暗里发一点光，不必等候炬火。
此后如竟没有炬火：我便是唯一的光。              ------鲁迅《热风》

## 联系

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
{% endfor %}
