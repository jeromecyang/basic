---
layout: page
title: 美洲
permalink: /americas/
---

{% assign regions = "US Northeast,US South,US Midwest,US West,Alaska,North America,Caribbean,Central America,South America" | split: "," %}
{% include area-map.html regions=regions center="30,-90" %}

## 美國東北部

{% include links-list.html tag="US Northeast" %}

## 美國南部

{% include links-list.html tag="US South" %}

## 美國中西部

{% include links-list.html tag="US Midwest" %}

## 美國西部

{% include links-list.html tag="US West" %}

## 阿拉斯加

{% include links-list.html tag="Alaska" %}

## 北美洲

{% include links-list.html tag="North America" %}

## 加勒比海

{% include links-list.html tag="Caribbean" %}

## 中美洲

{% include links-list.html tag="Central America" %}

## 南美洲

{% include links-list.html tag="South America" %}