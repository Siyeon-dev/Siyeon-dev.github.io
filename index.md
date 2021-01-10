---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---
{: .text-grey-dk-100}


# 안녕하세요.

성장하는 것을 좋아하는 개발자 박시연(Siyeon Park)입니다.프론트앤드 개발과 비즈니스 및 기획에 관심이 많습니다. 주로 책을 읽고 글을 쓰거나 기타를 치면서 시간을 보냅니다. 사람들과 함께 문제를 해결하는 과정에서 행복감을 느끼며, 따뜻한 커피☕️ 와 재즈🎷 를 가장 좋아합니다. 저에 대해서 궁금한 점이 있으시다면 <siyeon.dev@gmail.com>로 연락 주세요. 감사합니다.
{: .fs-4 .fw-300 }

[View it on GitHub](https://github.com/siyeon-dev)
{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
---
{: .fs-6 }

최근 포스트

{% for post in site.posts %}

{{ post.title }} {{ post.date | date_to_long_string }}

{% endfor %}