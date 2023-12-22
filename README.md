# AEGEE-München website

Repository for the [AEGEE-München website](https://aegee-muenchen.org).

## Table of Contents

1. [Introduction](#introduction)
1. [Highly optimised website](#highly-optimised-website)
1. [AEGEE-München leaflet](#aegee-london-leaflet)
   1. [Fonts](#fonts)
   1. [Precedents](#precedents)
   1. [Why the leaflet is in Photoshop format and not Illustrator?](#why-the-leaflet-is-in-photoshop-format-and-not-illustrator)

## Introduction

The website is vanilla JavaScript, HTML and CSS bundled with Gulp. It doesn't use any toolset or front-end framework like jQuery, Angular or React. It's served statically from [GitHub Pages](https://pages.github.com), hosting service with no costs. We don't make use of any CMS. No WordPress, Wix or similar. The [`docs`](https://github.com/AEGEE-Munchen/aegee-muenchen.org/tree/master/docs) folder is the final distributable page that is delivered when visiting [`aegee-muenchen.org`](https://aegee-muenchen.org). GitHub Pages allows to use your [own custom domain](https://help.github.com/en/articles/using-a-custom-domain-with-github-pages).

If you're the IT responsible for your antenna, you like our website and you'd like to use it, feel free to fork the repo, make the necessary changes and republish the website for your own antenna. It would be the best honour [Tony](https://github.com/AntonioRedondo), the original author of the website. Please remember to leave the footer with the link to the original repo and the link to [Tony's GitHub](https://github.com/AntonioRedondo).

<img src="https://github.com/AEGEE-Munchen/aegee-muenchen.org/raw/master/readmeImages/1.jpg" width="900px" />
<img src="https://github.com/AEGEE-Munchen/aegee-muenchen.org/raw/master/readmeImages/2.jpg" width="900px" />
<img src="https://github.com/AEGEE-Munchen/aegee-muenchen.org/raw/master/readmeImages/3.jpg" width="900px" />
<img src="https://github.com/AEGEE-Munchen/aegee-muenchen.org/raw/master/readmeImages/m.jpg" width="900px" />

## Highly optimised website

The website is optimised to load ultrafast. It follows the best performance, accessibility and rest of web practices. It gets the below [Lighthouse](https://github.com/GoogleChrome/lighthouse) score. You can check it yourself! Just open the Dev Tools on Chrome, click the Audits tab and generate a new report.

<img src="https://github.com/AEGEE-Munchen/aegee-muenchen.org/raw/master/readmeImages/Lighthouse.png" width="900px" />

## AEGEE-München leaflet

I have also designed an A4 double-sided leaflet that introduces AEGEE-München as a local antenna and explains what the organisation offers at European level. The leaflet is ready to be downloaded and customised for the needs of any other AEGEE antenna. The design shallowly follows the guidelines set on the [AEGEE’s Visual Identity](https://www.zeus.aegee.org/portal/resources/pr-materials). However I decided to take some liberties and simplify the number of colours (only yellow, white and blue) and design elements on the final art. The leaflets closely aligns with the AEGEE-München website design.

Download the PSD file [here](https://raw.githubusercontent.com/AEGEE-Munchen/aegee-muenchen.org/master/AEGEE-München-leaflet.psd).

<img src="https://github.com/AEGEE-Munchen/aegee-muenchen.org/raw/master/readmeImages/leaflet-AEGEE-München.jpg" width="900px" />

### Fonts

The leaflet uses 3 different fonts. All available from Google Fonts. Bebas Neue is the well-known font used for titles in AEGEE. The font recommended from AEGEE for small texts is Open Sans. But I prefer to use Source Sans Pro since it's very similar but it has better low level adjustments. Finally Roboto Slab is used for some lines among the leaflet. It’s a serif font not mentioned in the Visual Identity. But the other two fonts are sans serif and to my mind some sort of cold feeling it’s conveyed if no serif font is used.

- [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue)
- [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
- [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab)

### Precedents

AEGEE-Europe also [offers a leaflet](https://www.zeus.aegee.org/portal/resources/pr-materials) (scroll down the page to see it) to help to promote the organisation. However in my opinion this leaflet contains too much text, too much unused white space, text looks cluttered and it contains no pictures (apart from the blue ones used as background). There was a big margin for improvement and that’s why I created the new design.

<img src="https://github.com/AEGEE-Munchen/aegee-muenchen.org/raw/master/readmeImages/leaflet-AEGEE-Europe.jpg" width="900px" />

### Why the leaflet is in Photoshop format and not Illustrator?

I don't have Illustrator experience. However this doesn't suppose a problem. The dimensions of the image are 3508x2480, which means that for an A4 sheet the density is 300dp. If you're worried that when exporting the leaflet to PDF text won't be selectable because it will be an image instead, I'll say that's the wrong approach. The leaflet is only meant to be distributed in printed format. If you want to promote your antenna in digital format you should create a website and share the link, not making available the leaflet in PDF format.
