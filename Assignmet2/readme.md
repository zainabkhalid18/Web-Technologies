# HTML Newspaper Recreation - Daily Jang Karachi (First Edition)

## Student Information
- **Name:** Zainab Khalid
- **Roll Number:** 22P-9061
- **Section:** BCS-8A

## Original Newspaper
- **Name:** Daily Jang — روزنامہ جنگ (Urdu)
- **Date:** Tuesday, October 14, 1947
- **Edition:** First Karachi Edition (Vol. I, No. 1)
- **Source:** Personal scan of original historical newspaper print

## Project Description
This project recreates the front page of the very first Karachi edition of Daily Jang, published on October 14, 1947 — just two months after Pakistan's independence. Founded by Mir Khalil-ur-Rahman in Delhi in 1939 and relocated to Karachi after Partition, this historic edition covered the arrest of Muslim leaders by Nehru's government, the refugee crisis overwhelming Karachi, and the deteriorating situation in Kashmir. The recreation uses HTML5 only with inline styles to faithfully replicate the original's dense six-column broadsheet layout, aged newsprint aesthetic, and multi-article format.

## Features Implemented
- Semantic HTML5 tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Six-column broadsheet layout using an HTML `<table>` matching the original newspaper's grid
- Proper heading hierarchy: `<h1>` (masthead title), `<h2>` (lead headline), `<h3>` (article titles), `<h4>` (brief titles)
- Two nested `<table>` elements — the main 6-column layout and a market rates data table
- Unordered lists (`<ul>`) for refugee crisis facts and notices board
- Three `<img>` tags with descriptive `alt` attributes (original scan, Quaid address photo)
- HTML comments explaining every major section
- Inline `style` attributes only — no external CSS files or JavaScript used anywhere
- Consistent 2-space indentation throughout
- Aged newsprint colour scheme reflecting 1947 print aesthetics

## Challenges Faced
The main challenge was recreating a six-column broadsheet layout using only HTML tables and inline styles, without access to modern CSS Grid or Flexbox. This was solved by using a single master `<table>` with six `<td>` columns sized as percentages and separated by border-right styling. A secondary challenge was accurately translating the Urdu headline content from the 1947 original into rephrased English while preserving the historical context, which required research into events in Pakistan during October 1947.
