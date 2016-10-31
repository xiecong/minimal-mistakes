---
layout: single
author_profile: true
permalink: /
---
Hi, I am Cong Xie. I am a Ph.D. candidate under the supervision of [Prof. Klaus Mueller](http://www3.cs.stonybrook.edu/~mueller/) at [Stony Brook University](http://www.stonybrook.edu/).
I received master degree in [Zhejiang University](http://www.zju.edu.cn/), under the supervision of [Prof. Wei Chen](http://www.cad.zju.edu.cn/home/chenwei/).
My research interest is Data Visualization and Visual Analytics.

Email: coxie AT cs DOT stonybrook DOT com
            
You can also download my [full CV](http://www3.cs.stonybrook.edu/~coxie/homepage_files/CV_Cong.pdf).



{% include base_path %}
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
