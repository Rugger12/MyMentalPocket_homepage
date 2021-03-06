---
title: My Mental Pocket 
subtitle: A platform to help overcome stress<br /> Made by <a href="https://digitalhealthcare.or.kr">HY Digital Healthcare Center</a> & <a href="https://www.navercloudcorp.com/">Naver Cloud</a> & <a href="http://www.atommerce.com/">Atommerce</a>.
layout: layouts/base.njk
---
<img src="https://github.com/Rugger12/MyMentalPocket_homepage/blob/master/src/site/images/MyMentalPocket_LOGOb.png?raw=true" width="150" alt="logo">


## 우울 할 때 찾아갈 수 있는 모두의 플랫폼 

마이멘탈포켓은 다음의 서비스를 제공합니다.

- 우울할 때 인공지능 챗봇 친구 "포키"를 만나러 오세요.
- 대화를 나누면 "포키"가 웰니스 게임을 추천해줍니다.


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

<!-- ## Links from an external data source

These links were sourced from [naver.com](https://www.hawksworx.com/feed.json) at build time.

<ul class="listing">
{%- for item in hawksworx.entries.slice(0,3) -%}
  <li>
    <a href="https://digitalhealthcare.or.kr">HY Digital Healthcare Center</a>
  </li>
{%- endfor -%}
</ul> -->

## 마이멘탈포켓 서비스 계획

```bash
# 마이멘탈포켓의 서비스 발전단계
1. 정신건강(정서장애) 해결을 위한 포털 지향
2. 사용자 데이터 유입 통로
3. 사용자에게 다양한 웰니스 게임 서비스를 제공 연결시켜주는 포털서비스
   (내부: 신체활동게임, 외부: 다양한 웰니스게임 서비스) 

# 포키의 성장 계획
1 단계: 우울관련 정보 제공 챗봇 서비스
2 단계: 신체활동 게임 등의 추천 웰니스 게임 서비스
3 단계: 개별 상담 챗봇 [+ 카운셀러, 사용자를 위한 데이터 대시보드 제공]
4 단계: 정신건강 전문의 역할의 챗봇서비스


```


#마이멘탈포켓, #mymentalpocket, #"마이 멘탈 포켓", #"My Mental Pocket"


