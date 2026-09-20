# Project 1 — TODO Checklist

Tick these off as you go. Point values match the rubric.

## index.html — 20 pts
- [ ] Header, nav, and `<h1>`  *(given in the starter — reuse it everywhere)*
- [ ] "On Air Now" `<section>` with show, DJ, and time block
- [ ] "Recently Played" list, 5+ tracks, title and artist each marked up distinguishably (`<cite>`, `<strong>`, `<em>`)
- [ ] Station history `<article>`, 2+ paragraphs, with the studio image + real alt text
- [ ] `<aside>` featuring one show
- [ ] Google Maps `<iframe>` **with a `title` attribute**
- [ ] `<footer>` with `<address>`, tel: link, mailto: link, social nav, copyright

## schedule.html — 20 pts
- [ ] `<table>` with `<caption>`, `<thead>`, `<tbody>`
- [ ] 7 day columns + a time-block column
- [ ] 5+ time-block rows
- [ ] `scope="col"` on every column header, `scope="row"` on every row header
- [ ] At least one `colspan` or `rowspan`
- [ ] Cell counts balance on every row (count carefully — this is where people lose points)
- [ ] 4+ show profile `<section>`s with image, genre, air time, description
- [ ] `<dl>` glossary with 4+ `<dt>`/`<dd>` pairs

## request.html — 20 pts
- [ ] `<form method="post">` with a placeholder `action`
- [ ] 2+ `<fieldset>`s, each with a `<legend>`
- [ ] `text`, `email`, `tel` inputs for listener info
- [ ] Song title + artist, both `required`
- [ ] `<select>` with `<optgroup>` for weekday vs weekend shows
- [ ] `type="time"` input
- [ ] `<textarea>` with `maxlength`
- [ ] Radio group (same `name`, different `value`) for on-air name
- [ ] 3+ genre checkboxes (same `name`)
- [ ] Submit **and** reset buttons
- [ ] `<aside>` with the request rules

## join.html — 15 pts
- [ ] 2+ `<article>`s describing crew roles
- [ ] Crew roles `<table>` with caption, `<thead>`, 4+ rows, `scope` on all headers
- [ ] Application form: name, FSU email, phone, class standing `<select>`
- [ ] `type="date"` start date
- [ ] `type="number"` hours with `min` and `max`
- [ ] Experience `<textarea>`
- [ ] `required` terms checkbox
- [ ] `<ol>` of what happens after applying

## Everything else — 25 pts
- [ ] Semantics & structure (12): header/nav/main/section/article/aside/footer used correctly, one h1, no skipped levels, identical nav
- [ ] Accessibility & validation (8): zero W3C errors, alt text, label pairing, title on the map iframe
- [ ] Code organization (5): indentation, section comments, relative paths, no CSS, no JS, no media files
