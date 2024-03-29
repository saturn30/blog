---
title: "쏙쏙 들어오는 함수형 코딩 후기"
date: 2023-01-29
description: "쏙쏙 들어오는 함수형 코딩 후기"
summary: "쏙쏙 들어오는 함수형 코딩 후기"
slug: "functional-programming-book-review"
draft: false
categories: ["study"]
tags: ["book-review"]
---

오랜만에 글 쓴다. ㅎㅎ

함수형 프로그래밍에 대해 이름만 알지 제대로 잘 몰라서 개념 파악하려고 읽어봤다.

이 책에서 핵심적으로 다루는 내용은 코드에서 액션 / 계산 / 데이터를 분리하는 것과 일급추상으로 함수 재사용성을 높이는 방법에 대해서다.

액션 / 계산 / 데이터 개념은 굉장히 간단하면서도 좋은 코드를 설계하는데 도움이 많이 되는 내용이다.
요약하면 아래와 같다.

- 액션 - 부수효과(사이드 이펙트)를 일으키는 코드. 실행 시점이나 횟수등에 영향을 받는다.
- 계산 - 부수효과를 일으키지 않는 순수 함수. 전달받은 인자에만 의존하며 같은 입력값에 대해 항상 같은 결과를 반환함
  - 계산은 예측 가능하고 테스트를 짜기 쉽다.
- 데이터 - 이벤트에 대한 결과물. 계산과 비슷하나 실행할 필요가 없고, 그 자체로 정보를 지님.
- 프로그래밍에서 부수 효과를 완전히 제거하는것은 불가능하다.
  - 액션에서 계산에 해당하는 코드를 최대한 분리하여 액션을 줄이고 잘 격리시키는 것이 최선

일급 추상은 고차함수 개념을 이용해 함수 재사용성을 높이는 방법을 설명한다.

굉장히 쉽고 재미있게 설명하는 함수형 프로그래밍 입문서다. 재밌게 읽었다.
