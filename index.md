---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/"><span>Blog</span></a></li>
            <li style="text-align:center"><a href="/opinion"><span>Opinion</span></a></li>
            <li style="text-align:right"><a href="/project"><span>Project</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.blog %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
        <p style = 'position: absolute; bottom: 0; color: #ccc; margin-left: 10px; margin-bottom: 15px; opacity: 0.8; font-size: 12px;'>
            Copyright &copy; 2014 - Theme by <a href = 'https://github.com/beiyuu/Github-Pages-Example '>BeiYuu</a>
        </p>
    </div>
</div>
