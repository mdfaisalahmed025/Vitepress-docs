---
layout: home

hero:
  name: Adocs
  text: Static docs template built with VitePress.
  image:
    src: /logo.svg
    alt: Adocs logo
  tagline: A free to use template for creating docs for your projects
  actions:
    - theme: brand
      text: Get Started
      link: /get-started
    - theme: alt
      text: View on GitHub
      link: https://github.com/evavic44/adocs-template



link: https://github.com/evavic44/adocs-template

features:
  - icon: ⚡️
    title: Adocs, The DX that can't be beat
    details: Lorem ipsum...
  - icon: 🎉
    title: Power of Vue meets Markdown
    details: Lorem ipsum...
  - icon: 🔥
    title: Simple and minimal, always
    details: Lorem ipsum...
  - icon: 🎀
    title: Stylish and cool
    details: Lorem ipsum...

  - icon: ⚡️
    title: Adocs, The DX that can't be beat
    details: Lorem ipsum...
  - icon: 🎉
    title: Power of Vue meets Markdown
    details: Lorem ipsum...
  - icon: 🔥
    title: Simple and minimal, always
    details: Lorem ipsum...
  - icon: 🎀
    title: Stylish and cool
    details: Lorem ipsum...

---

---

| Tables        |      Are      |  Cool |
| ------------- | :-----------: | :----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |

---


::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::

<script setup>
import { useData } from 'vitepress'

const { theme } = useData()
</script>

<template>
  <h1>{{ theme.footer.copyright }}</h1>
</template>


