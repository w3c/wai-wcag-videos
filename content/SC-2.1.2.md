---
title: "SC 2.1.2 No Keyboard Trap in WCAG 2 Videos"

lang: en   # Change "en" to the translated-language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2021-@@-@@   # Put the date of this translation YYYY-MM-DD (with month in the middle)

github:
  repository: w3c/wai-wcag-videos
  path: content/SC-2.1.2.md    # Add the language shortcode to the middle of the filename, for example: content/index.fr.md
permalink: /SC-2.1.2/   # Add the language shortcode to the end, with no slash at end, for example: /link/to/page/fr

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

This page provides the script for Success Criterion 2.1.2 No Keyboard Trap of the [WCAG 2 Videos](https://wai-wcag-videos.netlify.app/overview/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Background

* [Success Criterion 2.1.2](https://www.w3.org/TR/WCAG22/#no-keyboard-trap)
* [Understanding SC 2.1.2](https://www.w3.org/WAI/WCAG22/Understanding/no-keyboard-trap.html)
* [Script Outline for SC 2.1.2](https://www.w3.org/WAI/EO/wiki/Video-Based_Resources/WCAG_Requirements#SC2-1-2)
* [Survey Results for SC 2.1.2](https://www.w3.org/2002/09/wbs/35532/Videos_WCAG_Squirrel/results#xSC212)

## Notes

* Initial description: Person with motor disabilities using a mouth stick is not stuck in a form field
* Updated description: [Brami](https://wai-wcag-videos.netlify.app/overview/#brami-he) is not stuck in a form field using mouth stick to type

## Script

| Scene | Time | Audio | Visual |
| ----- | ---- | ----- | ------ |
| 1 | 0:00 - 0:@@ | Brami is quadriplegic and uses a mouth stick to type on his keyboard. He uses the Tab-key to move between links, form fields, and other controls. | We see Brami using a mouth stick to type. We see him pressing the Tab-key and the focus moving from one form field to the next. |
| 2 | 0:00 - 0:@@ | Unfortunately some applications do not support this. For example, this date picker popped up when he tabbed into the date field. When Brami continues tabbing he is sent in circles within this date picker and cannot continue with other parts of the form. Also pressing escape and enter keys didn't close this date picker. | We zoom in to that part of the form - when Brami tabs into the field, a date picker is opened and the focus is moved there. We see Brami continuing to tab and the focus going in circles within the widget. |
| 3 | 0:00 - 0:@@ | It took Brami a while to find out that the Backspace key closes the date picker. He was not used to this unusual behavior, and was about to give up using the application altogether. | We see Brami annoyed trying different keys. We see him pressing the Backspace-key and him looking surprized that the widget finally disappeared. |
| 4 | 0:00 - 0:@@ | After he contacted the application owner and explained the problem they: added the escape and enter keys as further ways of closing the date picker; added a close button in the date picker; and added a small note before the date picker saying that the escape key closes it. | We see the date picker transition from the old version to the new. The new version has an additional "X" (close) button and a small instruction above it saying "ESC to close" or such. |
| 5 | 0:00 - 0:@@ | Brami is now a happy customer | We see Brami typing away with his mouth stick. |
