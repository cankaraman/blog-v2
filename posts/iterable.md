---
title: Iterable method usage in Flutter
description: This is about the most commonly used Iterable methods on Dart
date: 2022-05-26
tags:
  - flutter
  - dart
layout: layouts/post.njk
---

Flutter has a very declarative way of building UI. Some of Dart's Iterable methods makes this easier for us.

```dart
Column(
  children:[
    Text('Here are some widgets')
    someDataList.map((e) => myWidget(e))
  ]
)
```

That's nice.
