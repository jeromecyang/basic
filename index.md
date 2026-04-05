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

《旅行熱炒店：世界地理人文探索頻道》是一個從旅行經驗出發的PODCAST節目。我們不只分享旅行故事，更重要的是：透過旅行經驗去認識各地的地理、歷史、人文與社會議題。

# 最新單集

<div class="entries-grid">
  {% assign latest_episodes = site.posts | where: "layout", "episode" %}
  {% for post in latest_episodes limit:2 %}
    {% include entry.html %}
  {% endfor %}
</div>

# 地圖索引

{% assign regions = "Northeast Asia,Southeast Asia,South Asia,Central Asia,Oceania,Northern Europe,Western Europe,Central Europe,Eastern Europe,Southeastern Europe,Southern Europe,Caucasus,Middle East,North Africa,West Africa,East Africa,Southern Africa,US Northeast,US South,US Midwest,US West,Alaska,North America,Caribbean,Central America,South America" | split: "," %}
{% include area-map.html regions=regions center="30,0" %}
  