---
title: Some Professional JavaScript Tips
cover: javascript-featured.png
date: 2020-03-20
description: In this article I share some interesting tips of the JavaScript language that I am learning and I want to share with you..
tags: ['post','JavaScript']
hide: false
---

The first tip I want to share is about the iteration procedure on an array. We all know the classic procedure:

```js
  for(const i=0;i<10;i++){
    //do something with every i
  }
```
But we also have the expression *for-of*, which loops through the elements in an iterable object, for example an array:

```js
  for(const i of [1,2,3,4,5]){
    console.log(i) //1,2,3,4,5
  }
```
