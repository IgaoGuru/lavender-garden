---
title: About this site
---

## How it works
Zettelgarden is powered by Jekyll, a static website generator. The site is served as a Netlify deployment based on my github repo. Jekyll output the notes I have written in markdown as html.

## About the theme
I did not write the code for the site. [Maxime Vaillancourt](https://maximevaillancourt.com/) did that and the source code is available as a[ github template repo](https://github.com/maximevaillancourt/digital-garden-jekyll-template) under MIT License. There are many other themes built by amazing people if you wish to make your own digital garden.

The theme supports modern double bracket link syntax to other notes and it creates backlinks automatically. It mimics the functions of softwares such as [Roam Research](https://roamresearch.com/) and [Obsidian MD](https://obsidian.md/). There is also link previews on hover and an interactive graph visualization to show the notes are connected.

## An overview of my process
I copy just the permanent notes from my Zettelkasten system to the `_notes` folder section using a bash script periodically. Since I depent on [Logseq](https://logseq.com/) for most of my daily note taking I cannot use the files directly as formating inside wouldn't work for jekyll. I edit the files to be more jekyll friendly using Obsidian MD with the `_notes` folder as the vault. Once I am done I commit the changes to my the Zettelgarden repo.  [Nelify](https://netlify.app/) deploys the repo to give you the site that you see now.

Note: You can connect forestry.io to serve as a CMS to your site if you are into that sort of thing. The whole logseq to obsidian to Zettelgarden process is very new and I have to address some friciton that exists now. I will write about the process in depth once I have ironed out the friction points.

Go to [[Starts Here]] if you feel lost