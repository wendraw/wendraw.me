---
title: Projects - wendraw
display: Projects
description: List of projects that I am proud of
wrapperClass: 'text-center'
art: dots
projects:
  Current Focus:
    - name: 'Video Editor'
      link: 'https://github.com/AiDesignLabs/video-editor'
      desc: 'A video editor like capcut'
      icon: 'i-carbon-video'
    - name: 'Regex Doctor'
      link: 'https://github.com/antfu/regex-doctor'
      desc: 'Monitor RegExp to Improve Performance'
      icon: 'i-material-symbols:regular-expression saturate-0'

  Starter Templates:
    - name: 'Starter Monorepo'
      link: 'https://github.com/wendraw/starter-monorepo'
      desc: 'Monorepo Project Starter Template'
      icon: 'i-carbon-campsite'

---

<!-- @layout-full-width -->

<ListProjects :projects="frontmatter.projects" />
