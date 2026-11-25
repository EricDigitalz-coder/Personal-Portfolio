# Web Developer & AI Automation Expert — Personal Portfolio (HTML Foundations Capstone)

## Project Description
A multi-page personal portfolio website built exclusively with **semantic HTML5**—with zero CSS, JavaScript, or external frameworks. The project demonstrates mastery of document structure, accessible navigation, cross-folder relative routing, tabular data presentation, native multimedia embedding, and W3C markup validation.

## Pages Included
1. `index.html` — Homepage featuring hero introduction, portrait figure, native audio introduction, featured projects with video workflow demo, and external resource links.
2. `about.html` — Professional background, workstation figure, technical skills description list (`<dl>`), and ordered engineering process (`<ol>`).
3. `services.html` — Core service offerings and a structured comparison data table (`<table>`) with caption, header scopes, body, and spanning footer.
4. `blog.html` — Technical articles (`<article>`) with publication timestamps (`<time>`) and internal fragment navigation.
5. `contact.html` — Direct contact channels (`<address>`, `mailto:`, `tel:`), external developer profiles, and call-to-action routing.
6. `pages/application.html` — Multi-section project inquiry form (`<form>`) housed in a child directory to demonstrate parent-folder (`../`) relative navigation.

## HTML Features Used
- **Semantic Landmarks:** `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, and `<address>`.
- **Text & Lists:** Headings (`<h1>`–`<h3>`), paragraphs (`<p>`), `<strong>`, `<em>`, `<code>`, `<small>`, unordered lists (`<ul>`), ordered lists (`<ol>`), and description lists (`<dl>`, `<dt>`, `<dd>`).
- **Navigation & Linking:** Root-to-child relative links (`./pages/application.html`), child-to-parent relative links (`../index.html`), same-page fragment links (`#featured-projects`), email links (`mailto:`), telephone links (`tel:`), and secure external links (`rel="noopener noreferrer"`).
- **Multimedia & Graphics:** Responsive dimension attributes, descriptive `alt` attributes, decorative empty `alt=""`, `<figure>`, `<figcaption>`, native `<audio controls>`, and `<video controls poster="...">`.
- **Tabular Data:** `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<th scope="col">`, `<th scope="row">`, and `colspan`.
- **Accessible Forms:** `<form>`, `<fieldset>`, `<legend>`, explicit `<label for="...">` pairings, `text`, `email`, `tel`, `select`/`option`, `radio`, `checkbox`, `textarea`, native validation constraints (`required`, `minlength`, `maxlength`, `pattern`), and `<button type="submit">`.

## What I Learned
- **Structure Precedes Styling:** Valid, semantic HTML creates an immediately readable, navigable, and accessible document hierarchy even with zero CSS applied.
- **Relative Path Discipline:** Managing links between root files (`./`) and nested directories (`../`) requires careful path verification to prevent broken assets and navigation links.
- **Accessibility by Default:** Native HTML controls (`<button>`, `<label>`, `<th scope>`) provide built-in keyboard focus and screen-reader announcements without extra scripting.

## Challenges Encountered
- **Cross-Folder Asset Paths:** Ensuring that `pages/application.html` navigated cleanly back to root pages (`../index.html`) while root pages linked forward (`./pages/application.html`) required systematic testing across every link.
- **Strict W3C Compliance:** Eliminating obsolete attributes and ensuring every `<section>` and `<article>` maintained a logical heading hierarchy (`<h1>` followed by `<h2>`, never skipping levels).

## Resources & Media Attributions
- **HTML Specification & Reference:** MDN Web Docs (`https://developer.mozilla.org/en-US/docs/Web/HTML`)
- **Markup Validation:** W3C Nu HTML Checker (`https://validator.w3.org/nu/`)
- **Media Assets (`images/` & `media/`):** Custom portfolio portrait, workstation photography, divider graphic, terminal poster, and spoken voiceover generated specifically for this project.