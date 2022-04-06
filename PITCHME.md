---
marp: true
title: Slack future app platform
description: A simple walkthrough about Slack next generation app platform
theme: uncover
paginate: true
_paginate: false
---

<!-- ![bg](./assets/gradient.jpg) -->

![bg](#123) ![](#fff)

# <!--fit--> Slack future app platform

https://api.slack.com/future/overview

<style scoped>a { color: #eee; }</style>

<!-- This is presenter note. You can write down notes through HTML comment. -->

---

<!-- ![Marp bg 60%](https://raw.githubusercontent.com/marp-team/marp/master/marp.png) -->

### Current struggle

- Dev flow & deployment
- Complex settings & permissions
- Not works well with recently Slack bulit-in features

## 😭

---

![bg](#123) ![](#fff)

#### <!--fit--> 👉 New app architecture!

##### <!--fit--> [Triggers](https://api.slack.com/future/workflows/triggers) | [Workflows](https://api.slack.com/future/workflows) | [Functions](https://api.slack.com/future/workflows/functions)

#### <!--fit--> ![slackapp](https://a.slack-edge.com/bf8dff7/img/api/future/slack-apps-high-level@2x.png)

---

## <!--fit--> **Something you needs before kickoff!**

- Install [deno](https://deno.land/#installation)
- Install [Slack CLI](https://api.slack.com/future/tools/cli/download)
- TypeScript(?)

---

![bg right:20% fit](https://deno.land/logo.svg)

### <!--fit--> What is deno?

> A modern runtime for JavaScript and TypeScript. created by Ryan Dahl

<style scoped>
  li {
    font-size: .7rem;
    text-align: center;
  }
</style>

- [10 Things I Regret About Node.js](https://www.youtube.com/watch?v=M3BM9TB-8yA)
- [Deno is a New Way to JavaScript](https://www.youtube.com/watch?v=1gIiZfSbEAE)

---

### A better Node.js? 😆

- Better security
- No more centrialized module system
- Follow the standard
- Rust & TypeScript (比較酷 😄)

---

![bg](#123) ![](#fff)

### Don't panic 😱

Let's walkthrough an easy example.

---

![bg 40% opacity blur](https://avatars.githubusercontent.com/u/173408?v=4)

### Shared by SY ([@siygle](https://github.com/siygle))
