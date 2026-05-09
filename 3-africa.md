---
layout: page
title: 非洲
permalink: /africa/
image: https://i.imgur.com/I8HADSn.png
---

{% assign regions = "North Africa,West Africa,East Africa,Southern Africa" | split: "," %}
{% include area-map.html regions=regions center="0,20" zoom="3" %}

## 北非

{% include links-list.html tag="North Africa" %}

## 西非

{% include links-list.html tag="West Africa" %}

## 東非

{% include links-list.html tag="East Africa" %}

## 南非

{% include links-list.html tag="Southern Africa" %}
