---
title: "SC 1.3.5 Identify Input Purpose in WCAG 2 Videos"

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

This page provides the script for Success Criterion 1.3.5 Identify Input Purpose of the [WCAG 2 Videos](https://wai-wcag-videos.netlify.app/overview/).

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
* Updated description: [Jonathan](https://wai-wcag-videos.netlify.app/overview/#jonathan-he), has dyscalculia, does not need to type form fields because they are properly identified to the browser that automatically completes them

## Script

| Scene | Time | Audio | Visual |
| ----- | ---- | ----- | ------ |
| 1 | 0:00 - 0:@@ | Jonathan has dyscalculia, which makes it difficult for him to work with numbers. This includes credit card numbers, phone numbers, and numbers in email addresses, usernames, and passwords. | We see Jonathan using a tablet computer. |
| 2 | 0:@@ - @:@@ | Recently Jonathan had difficulty logging into his employer's website. His username is based on an identification number and also the password includes numbers. | We see a form asking for "Username" and "Password", and he seems to have trouble typing in the username (he keeps reviewing the numbers and correcting mistake he made while typing). |
| 3 | @:@@ - @:@@ | Jonathan now uses a browser that allows him to store information that he types into input fields. It provides him an option to automatically complete the input fields when the information is requested again. | We see the form, with the browser showing different usernames that Jonathan can select from, to auto-complete the input field (these usernames are collected from previous entries on this website). |
| 4 | @:@@ - @:@@ | Fortunately his employer's website now uses the correct code to identify the purpose of input fields, so that they can be stored and automatically completed when Jonathan wants. | We see the form, then the underlying code is shown illustratively (not intended to be actually read), and the relevant attributes in the code highlighted (also illustratively). |
| 5 | @:@@ - @:@@ | Jonathan loves this feature because it saves him a lot of time and effort having to re-type the information each time it is requested. Jonathan can also use the saved entries for other websites that use correct coding of input fields. | We see Jonathan using the auto-complete for username (and maybe also password) on a different log-in page (for another website). |
