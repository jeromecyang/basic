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

# 地圖索引

{% include area-map.html %}

# 最新單集

<div class="entries">
  {% assign latest_episodes = site.posts | where: "layout", "episode" %}
  {% for post in latest_episodes limit:10 %}
    {% include entry.html %}
  {% endfor %}
</div>

前往[全部單集](/episodes)，尋找更多內容！

# 聯繫回饋

您可以透過下列管道聯繫，或是在收聽平台留言，我（主廚 Jerome）會親自回覆！

* [Facebook](https://www.facebook.com/travel.wok)
* [Instagram](https://www.instagram.com/travel.wok)
* [Email](mailto:travel.wok@ltsoj.com)
* [悄悄話匿名回饋](https://forms.gle/4v9Xc5PJz4geQp7K7)

所有商業合作、活動宣傳、書籍推廣皆非本店服務項目，若有以上這些需求請不要聯繫本店，謝謝。
