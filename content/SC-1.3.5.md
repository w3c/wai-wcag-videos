---
title: "SC 1.3.5 in WCAG 2 Videos"

lang: en   # Change "en" to the translated-language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2021-@@-@@   # Put the date of this translation YYYY-MM-DD (with month in the middle)

github:
  repository: w3c/wai-wcag-videos
  path: content/SC-1.3.5.md    # Add the language shortcode to the middle of the filename, for example: content/index.fr.md
permalink: /SC-1.3.5/   # Add the language shortcode to the end, with no slash at end, for example: /link/to/page/fr

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

This page provides the script for Success Criterion 1.3.5 of the [WCAG 2 Videos](https://wai-wcag-videos.netlify.app/overview/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Background

* [Success Criterion 1.3.5](https://www.w3.org/TR/WCAG22/#identify-input-purpose)
* [Understanding SC 1.3.5](https://www.w3.org/WAI/WCAG22/Understanding/identify-input-purpose.html)
* [Script Outline for SC 1.3.5](https://www.w3.org/WAI/EO/wiki/Video-Based_Resources/WCAG_Requirements#SC1-3-5)
* [Survey Results for SC 1.3.5](https://www.w3.org/2002/09/wbs/35532/Videos_WCAG_Squirrel/results#xSC135)

## Notes

* Initial description: [Person with dyslexia and dyscalculia does not need to type form fields because they are properly identified to the browser that automatically completes them](https://www.w3.org/WAI/standards-guidelines/wcag/new-in-21/#135-identify-input-purpose-aa)
* Updated description: [Preety](https://wai-wcag-videos.netlify.app/overview/#preety-she), has dyslexia and dyscalculia, does not need to type form fields because they are properly identified to the browser that automatically completes them

## Script

| Scene | Time | Audio | Visual |
| ----- | ---- | ----- | ------ |
| 1 | 0:00 - 0:@@ | Preety has dyslexia and dyscalculia, which makes it difficult for her to type things like a phone number, email address, username, and passwords. | We see Preety reading on a tablet computer at her desk at home (see [SC-1.3.2](https://wai-wcag-videos.netlify.app/sc-1.3.2/)). |
| 2 | 0:@@ - @:@@ | For example, she often has difficulty logging into the school's online learning platform. It is not a memory issue, she just confuses the numbers and letters when she is typing them because they are not real words. | We see a form asking for "Student ID" and "Password", and she seems to have trouble typing in the long Student ID number. |
| 3 | @:@@ - @:@@ | Fortunately the school website uses the correct code to identify the purpose of different input fields. On this page, she is asked to provide her Student ID number and a phone number or email address as contact information. | We see the from, then the underlying code with the relevant attributes in the code highlighted. |
| 4 | @:@@ - @:@@ | Preety's browser allows her to choose if she wants to store these inputs for different websites, so that she does not have to re-type them each time they are requested. | We see a browser dialog asking Preety if she wants to save the email address, and she accepts to store it for this website. |
| 5 | @:@@ - @:@@ | She allows her username and email address to be stored for her school website because they are used frequently. When these are requested, they are automatically filled by the browser and it saves Preety a lot of time and effort. | We see Preety browse to the same form again but this time her username is automatically filled in by the browser. |
