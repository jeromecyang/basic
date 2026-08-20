---
layout: page
title: 歐洲西亞
permalink: /europe/
image: https://i.imgur.com/V4p2j7a.png
---

{% assign regions = "Northern Europe,Western Europe,Central Europe,Eastern Europe,Southeastern Europe,Southern Europe,Caucasus,Middle East" | split: "," %}
{% include area-map.html regions=regions center="50,30" zoom="3" %}

## 北歐

{% include links-list.html tag="Northern Europe" %}

## 西歐

{% include links-list.html tag="Western Europe" %}

## 中歐

{% include links-list.html tag="Central Europe" %}

## 東歐

{% include links-list.html tag="Eastern Europe" %}

## 東南歐

{% include links-list.html tag="Southeastern Europe" %}

## 南歐

{% include links-list.html tag="Southern Europe" %}

## 高加索

{% include links-list.html tag="Caucasus" %}

## 中東

{% include links-list.html tag="Middle East" %}
