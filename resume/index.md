---
layout: home
---

<div class="index-content opinion">
    <div class="section">
        <ul class="artical-cate">
           <!-- <li class="on"><a href="{{ site.url }}"><span>Blog</span></a></li> 
            <li style="text-align:center"><a href="{{ site.url }}/opinion"><span>Opinion</span></a></li>
            <li style="text-align:right"><a href="{{ site.url }}/project"><span>Project</span></a></li>
            -->
            <!-- {% include catalog.md %} -->

           <li ><a href="{{ site.url }}"><span>Blog</span></a></li>
 <li  style="text-align:center"><a href="{{ site.url }}/project"><span>Project</span></a></li>
 <li class="on" style="text-align:right"><a href="{{site.urlg}}" target="view_window" ><span>Resume</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.opinion %}
            <li>
                <h2><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
