---
title: "SC 1.3.1 Info and Relationships in WCAG 2 Videos"

lang: en   # Change "en" to the translated-language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2021-@@-@@   # Put the date of this translation YYYY-MM-DD (with month in the middle)

github:
  repository: w3c/wai-wcag-videos
  path: content/SC-1.3.1.md    # Add the language shortcode to the middle of the filename, for example: content/index.fr.md
permalink: /SC-1.3.1/   # Add the language shortcode to the end, with no slash at end, for example: /link/to/page/fr

ref: /link/to/page/   # Translators, do not change this
changelog: /@@/changelog/
acknowledgements: /@@/acknowledgements/  # NEW: delete if don"t have a separate acknowledgements page. And delete it in the footer below.
license: creative-commons   # NEW: delete if not creative-commons

description:  # NEW: add a 150ish-character-description for social media   # translate the description
image: /content-images/wai-wcag-videos/social.png  # NEW: image for social media
feedbackmail: wai@w3.org  # NEW: delete this line if it’s an EOWG resource (the default is wai-eo-editors@w3.org)

# NEW: Footer below has several options, and not all will be relevant for specific pages. (Ask Shawn if questions.)

footer: >   # Translate words below, including "Date:" and "Editor:" Translate the Working Group name. Leave the Working Group acronym in English. Do *not* change the dates in the footer below.
   <p><strong>Date:</strong> Updated @@ Month 2021. First published Month 20@@. CHANGELOG.</p>
   <p><strong>Editors:</strong> @@name, @@name. <strong>Contributors:</strong> @@name, @@name, and <a href=”https://www.w3.org/groups/wg/@@wg/participants”>participants of the @@WG</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
   <p>Developed by the @@ Working Group (<a href="http://www.w3.org/WAI/@@/">@@WG</a>). Developed as part of the <a href="https://www.w3.org/WAI/@@/">WAI-@@ project</a>, @@co-funded by the European Commission.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides the script for Success Criterion 1.3.1 Info and Relationships of the [WCAG 2 Videos](https://wai-wcag-videos.netlify.app/overview/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Background

* [Success Criterion 1.3.1](https://www.w3.org/TR/WCAG22/#info-and-relationships)
* [Understanding SC 1.3.1](https://www.w3.org/WAI/WCAG22/Understanding/info-and-relationships.html)
* [Script Outline for SC 1.3.1](https://www.w3.org/WAI/EO/wiki/Video-Based_Resources/WCAG_Requirements#SC1-3-1)
* [Survey Results for SC 1.3.1](https://www.w3.org/2002/09/wbs/35532/Videos_WCAG_Squirrel/results#xSC131)

## Notes

* Initial description: Person with tremors is able to select a checkbox by clicking on the larger label
* Updated description: [Ilya](https://wai-wcag-videos.netlify.app/overview/#ilya-she) is able to understand and navigate page structures using screen reader

## Script

| Scene | Time | Audio | Visual |
| ----- | ---- | ----- | ------ |
| 1 | 0:00 - 0:@@ | Ilya is blind. Like many other blind computer users, she does not read Braille. She listens to a screen reader reading aloud what is on the screen. | Ilya is in an office space working at a desktop computer. She has headphones connected to the computer. |
| 2 | 0:@@ - @:@@ | [We hear the screen reader starting to read a web page] | We see Ilya's screen while she is navigating in a web page. The actions on the screen match the audio we hear from the screen reader. |
| 3 | @:@@ - @:@@ | Ilya's screen reader announces page structures, such as headings, lists, links, and table cells. [We hear the screen reader announce a heading then a list under that heading] | We continue to see the screen, and the individual page structures being highlighted by the screen reader as they are being read aloud. |
| 4 | @:@@ - @:@@ | Ilya's screen reader also provides functionality to navigate such page structures. For example, she can jump from one heading to the next. [We hear the screen reader announce one heading, then another heading that is obviously a sub-heading] | We continue to see the screen, and the individual page structures being highlighted by the screen reader as they are being read aloud. |
| 5 | @:@@ - @:@@ | Yet this only works when the page is coded correctly. Otherwise the entire page is one large block of text without any structural information, which is unusable for Ilya and many others. | We see a large block of text morph into HTML code with structures (indicated by spacing and indents in the code). We do not see the exact text/code, just that it changes from unstructured to structured. |
| 6 | @:@@ - @:@@ | Fortunately content authors at her company are trained to markup page structures. For example, to add headings to web pages and documents. | We see someone using a WYSIWYG editor to markup a piece of text as a heading, and adjust it to make it look like the headings we saw earlier. |
