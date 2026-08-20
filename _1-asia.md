---
layout: collection
title: 亞洲太平洋
permalink: /asia/
image: https://i.imgur.com/TyHKEk5.png
---

{% assign regions = "Northeast Asia,Southeast Asia,South Asia,Central Asia,Oceania" | split: "," %}
{% include area-map.html regions=regions center="30,120" %}

## 東北亞

{% include links-list.html tag="Northeast Asia" %}

## 東南亞

{% include links-list.html tag="Southeast Asia" %}

## 南亞

{% include links-list.html tag="South Asia" %}

## 中亞

{% include links-list.html tag="Central Asia" %}

## 大洋洲

{% include links-list.html tag="Oceania" %}
