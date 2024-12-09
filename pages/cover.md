---
# author field for exported PDF or PPTX
author: Alberto Pulito
# theme id, package name, or local path
theme: seriph
# background images
background: "./cover.jpg"
class: text-center
# enable Slidev's context menu, can be boolean, 'dev' or 'build'
contextMenu: "dev"
# enabled pdf downloading in SPA build, can also be a custom url
download: true
# filename of the export file
exportFilename: slidev-exported
# export options
# use export CLI options in camelCase format
# Learn more: https://sli.dev/guide/exporting.html
export:
  format: pdf
  timeout: 30000
  dark: false
  withClicks: false
  withToc: false
# defines the layout component applied to the slide
layout: cover
# enable presenter mode, can be boolean, 'dev' or 'build'
presenter: "dev"
---

# Scacchi e Creatività  
## L'arte di pensare fuori dagli schemi   
<span class="text-sm opacity-70">Un viaggio per sviluppare e liberare la creatività nel gioco.</span>

<div @click="$slidev.nav.next" class="absolute bottom-6 right-6 text-xl py-1" hover:bg="white op-10">
  <carbon:arrow-right />
</div>