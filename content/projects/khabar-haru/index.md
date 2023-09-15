---
title: Khabar Haru (News Aggregator)
seo_title: news aggregator
summary: A news aggregator for Nepali news. Removes the fuss of visiting ad-ridden news site, social media for checking news headlines.
description: A basic news agggregator that scrapes from Nepali news portals and serves them via a HTTP webserver. Written in go.
slug: khabar-haru
author: Roshan Lamichhane

draft: false
date: 2023-09-12T21:05:46+05:45
lastmod:
expiryDate:
publishDate: 2023-01-23

feature_image: banner-khabar.png
feature_image_alt: Image showing the web app.

project types:
  - Personal

techstack:
  - Go

live_url: https://khabar-haru.cyclic.app/
source_url: https://github.com/roshanlc/khabar-haru

newsletter: false
---

## Khabar Haru

> Khabar means `News` in Nepali.

It is a news agggregator that scrapes from Nepali news portals and serves them via a HTTP webserver. It scrapes the news sites in an hourly interval and stores them internally.

### Stack

- Go
- Go Templating

### Features

- Supports Ekantipur, BBC Nepali news and The Kathmandu Post
- Shows Daily Petroleum Prices
- Easily Deployable (single binary)
