---
title: My Mental Pocket
subtitle: A platform help to overcome your stress.<br /> Made by <a href="https://digitalhealthcare.or.kr">HY Digital Healthcare Center</a> & <a href="https://www.navercloudcorp.com/">Naver Cloud</a>, & <a href="http://www.atommerce.com/">atommerce</a>.
layout: layouts/base.njk
---


## 우울 할 때 찾아갈 수 있는 모두의 플랫폼

마이멘탈포켓은 다음의 서비스를 제공합니다.

- 우울할 때 인공지능 챗봇 친구 "포키"를 만나러 오세요.
- "포키"와 대화를 나누면 나눌수록 나에게 적합한 중재치료가 제공됩니다.


## Post pages

The pages found in in the posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

## Links from an external data source

These links were sourced from [naver.com](https://www.hawksworx.com/feed.json) at build time.

<ul class="listing">
{%- for item in hawksworx.entries.slice(0,5) -%}
  <li>
    <a href="https://digitalhealthcare.or.kr">HY Digital Healthcare Center</a>
  </li>
{%- endfor -%}
</ul>

## Running locally

```bash
# install the dependencies
npm install

# External data sources can be stashed locally
npm run seed

# It will then be available locally for building with
npm run start
```





