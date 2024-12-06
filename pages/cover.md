---
# author field for exported PDF or PPTX
author: Alberto Pulito
# theme id, package name, or local path
theme: seriph
# addons, can be a list of package names or local paths
# Learn more: https://sli.dev/guide/theme-addon.html#use-addon
addons: []
# background images
background: "./images/cover.jpg"
# title of your slide, will inferred from the first header if not specified
title: Scacchi e Creatività - L'arte di pensare fuori dagli schemi
info: |
  ## Slidev Template
  Presentation slides for chess entusiastic.

class: text-center
drawings:
  persist: false
# enabled pdf downloading in SPA build, can also be a custom url
download: true
# filename of the export file
exportFilename: slidev-exported
# defines the transition between the slide and the next one
# Learn more: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
mdc: true
# defines the layout component applied to the slide
layout: cover
---

# Scacchi e Creatività  
## L'arte di pensare fuori dagli schemi   
<span class="text-sm opacity-50">Un viaggio attraverso la storia e la creatività negli scacchi</span>

<div @click="$slidev.nav.next" class="absolute bottom-6 right-6 text-xl py-1" hover:bg="white op-10">
  <carbon:arrow-right />
</div>