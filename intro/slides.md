---
# author field for exported PDF or PPTX
author: Alberto Pulito
# enable Slidev's context menu, can be boolean, 'dev' or 'build'
contextMenu: "dev"
# enabled pdf downloading in SPA build, can also be a custom url
download: true
# filename of the export file
exportFilename: slide-intro
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
info: |
  # Scacchi e Creatività  
  ## L'arte di pensare fuori dagli schemi
# enable presenter mode, can be boolean, 'dev' or 'build'
presenter: "dev"
# theme id, package name, or local path
theme: seriph
---

---
src: ./pages/cover.md
---

---
src: ./pages/info.md
---

---
src: ./pages/trip.md
---

---
src: ./pages/goal_fake.md
---

---
src: ./pages/goal.md
---
