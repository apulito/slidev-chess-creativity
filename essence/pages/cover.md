---
# author field for exported PDF or PPTX
author: Alberto Pulito
# background images
background: "./cover.jpg"
class: text-center
# enable Slidev's context menu, can be boolean, 'dev' or 'build'
contextMenu: true
# enabled pdf downloading in SPA build, can also be a custom url
download: true
# filename of the export file
exportFilename: slide-essence-creativity
# export options
# use export CLI options in camelCase format
# Learn more: https://sli.dev/guide/exporting.html
export:
  format: pdf
  timeout: 30000
  dark: false
  withClicks: false
  withToc: false
# information for your slides, can be a Markdown string
info: false
# defines the layout component applied to the slide
layout: cover
# enable presenter mode, can be boolean, 'dev' or 'build'
presenter: false
# theme id, package name, or local path
theme: seriph
title: Chess and creativity essence
---

# Scacchi e Creatività  
## L’essenza della creatività 

<div @click="$slidev.nav.next" class="absolute bottom-6 right-6 text-xl py-1" hover:bg="white op-10">
  <carbon:arrow-right />
</div>