---
title: Freiwillige Feuerwehr Hamburg-Eppendorf
description: Freiwillige Feuerwehr Hamburg-Eppendorf (F1951) - aktuelle Einsätze, unsere Fahrzeuge, das Feuerwehrhaus und Infos zum Mitmachen.
content_blocks:
- _bookshop_name: hero
  heading:
    title: Freiwillige Feuerwehr Eppendorf
    content: Technischer Zug - F1951
    align: start
  background:
    backdrop: /assets/img/hero.jpg
  illustration:
    image: /assets/img/logo_ff.png
    width: 12
  orientation: horizontal
  cover: true

- _bookshop_name: articles
  body_style: title
  heading:
    title: Einsätze
    align: start
  input:
    section: einsaetze
    sort: date
    nested: true
  limit: 9
  hide_empty: true
  more:
    title: Weitere Einsätze
    link: einsaetze/page/2/
  class: shadow border-0 card-zoom card-body-margin

- _bookshop_name: articles
  body_style: title
  heading:
    title: Aktuelles
    align: start
  input:
    section: aktuelles
    sort: date
    nested: true
  limit: 9
  hide_empty: true
  more:
    title: Weiteres Aktuelles 
    link: aktuelles/page/2/
  class: shadow border-0 card-zoom card-body-margin
---
