---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Qiusi</h1>
        <a href="http://weibo.com/2067726177/profile?topnav=1&wvr=6" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://mp.weixin.qq.com/s?src=3&timestamp=1495360991&ver=1&signature=8s4Cb4sdW2NVGDKQtRc3mJIN2bXcvARFd2mi-CjcotuPjYqS2Nic9ALb2J9DvAHxXXzIfVkUHhe-P*Ydfd9qEkU4TCpW3qz7yzjjOMhjcWnoPIhRd2rOlkNiu-EXp9enQ8tHuoBJu9kpz0dpBtFGUrEYlWK74kR-Y77Cr5ddYSs=" target="_blank"><img src="http://www.douban.com/favicon.ico" alt="" width="22"/></a>
        <a href="https://www.zhihu.com/people/lin-pan-3" target="_blank"><img src="http://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="22"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
