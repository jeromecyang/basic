---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
alt_title: 旅行熱炒店：世界地理人文探索頻道
actions:
  - label: "Spotify"
    url: "https://open.spotify.com/show/4ax4pKjk6P2GvPgXvJ3n85"
  - label: "Apple Podcasts"
    url: "https://podcasts.apple.com/tw/podcast/id1518914711"
  - label: "Youtube"
    icon: youtube
    url: "https://www.youtube.com/@travelwok"
  - label: "Facebook"
    icon: facebook
    url: "https://facebook.com/travel.wok"
  - label: "Instagram"
    icon: instagram
    url: "https://instagram.com/travel.wok"
---

《旅行熱炒店：世界地理人文探索頻道》是一個從旅行經驗出發的PODCAST節目。我們不只分享旅行故事，更重要的是：透過旅行經驗去認識各地的地理、歷史、人文與社會議題。 >> [更多關於旅行熱炒店](/about) <<

您可以透過地圖尋找有興趣的內容，或從更下方依照地區瀏覽不同主題！

{% assign regions = "Northeast Asia,Southeast Asia,South Asia,Central Asia,Oceania,Northern Europe,Western Europe,Central Europe,Eastern Europe,Southeastern Europe,Southern Europe,Caucasus,Middle East,North Africa,West Africa,East Africa,Southern Africa,US Northeast,US South,US Midwest,US West,Alaska,North America,Caribbean,Central America,South America" | split: "," %}
{% include area-map.html regions=regions center="30,0" %}

# 最新單集

<div class="entries-grid">
  {% assign latest_episodes = site.posts | where: "layout", "episode" %}
  {% for post in latest_episodes limit:2 %}
    {% include entry.html %}
  {% endfor %}
</div>

<!-- ## 主題地圖

<div class="entries-grid">
  {% assign latest_episodes = site.posts | where: "layout", "map" %}
  {% for post in latest_episodes limit:2 %}
    {% include entry.html %}
  {% endfor %}
</div>

## 旅行攻略

<div class="entries-grid">
  {% assign latest_episodes = site.posts | where: "featured", "true" %}
  {% for post in latest_episodes %} 
    {% include entry.html %}
  {% endfor %}
</div> -->

# 按地區瀏覽單集、地圖與旅行攻略

<h1 style="text-align: center; padding: 24px 0; background: url('https://i.imgur.com/TyHKEk5.png') center / cover no-repeat;"><a href="/asia" style="color: white; text-decoration: none; display: block; width: 100%;">亞洲太平洋</a></h1>

<h1 style="text-align: center; padding: 24px 0; background: url('https://i.imgur.com/V4p2j7a.png') center / cover no-repeat;"><a href="/europe" style="color: white; text-decoration: none; display: block; width: 100%;">歐洲西亞</a></h1>

<h1 style="text-align: center; padding: 24px 0; background: url('https://i.imgur.com/I8HADSn.png') center / cover no-repeat;"><a href="/africa" style="color: white; text-decoration: none; display: block; width: 100%;">非洲</a></h1>

<h1 style="text-align: center; padding: 24px 0; background: url('https://i.imgur.com/W8tsGzz.png') center / cover no-repeat;"><a href="/americas" style="color: white; text-decoration: none; display: block; width: 100%;">美洲</a></h1>

<h1 style="text-align: center; padding: 24px 0; background: url('https://i.imgur.com/6TTweoe.png') center / cover no-repeat;"><a href="/maps" style="color: white; text-decoration: none; display: block; width: 100%;">地圖</a></h1>

# 聯繫回饋

您可以透過下列管道聯繫，或是在收聽平台留言，我（主廚 Jerome）會親自回覆！

* [Facebook](https://www.facebook.com/travel.wok)
* [Instagram](https://www.instagram.com/travel.wok)
* [Email](mailto:travel.wok@ltsoj.com)
* [悄悄話匿名回饋](https://forms.gle/4v9Xc5PJz4geQp7K7)

所有商業合作、活動宣傳、書籍推廣皆非本店服務項目，若有以上這些需求請不要聯繫本店，謝謝。
