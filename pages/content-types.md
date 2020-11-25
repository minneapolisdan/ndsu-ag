---
layout: layouts/page.njk
title: Content types 
date: 2020-11-24
permalink: /content-types/index.html
eleventyNavigation:
  key: Content types
  order: 4
---
NDSU Ag & Ext has compiled a list of known content types, along with desired functionality, and outstanding questions. This list does not appear to be exhaustive based on the review of other components of this project (such as the Ag Hub, county extension offices, etc.).  Further discovery is needed to determine how these types interact across the entire Ag & Ext site.

**We have started an initial build plan draft below that will be expanded and revised as we continue to gather more information. See draft plan here:**

* See [Build plan draft](https://docs.google.com/document/d/1ubikpzz9qfGd5bDxCGCpTcKc-JsCyMPvYySkUo4nIKQ/edit?usp=sharing) -- if you have initial feedback on anything in this plan please post on Basecamp.

## Pages 

Basic pages are an essential content type in Drupal and they control all basic informational pages on a site. Examples from NDSU Ag’s current site include: https://www.ag.ndsu.edu/research/history and https://www.ag.ndsu.edu/pesticide/fumigation-resources-1.

* Landing pages
* Basic pages
* Destination pages* 

Typically we build a basic page content type for all standard content, and then a landing page content type for more advance/highly designed pages (including the homepage).  

**Questions:**

* In reading your notes it sounds like there is a difference in intended purpose for destination pages and landing pages, but from a functional perspective do these pages have fields or layouts that are different or unique enough to warrant two different content types?
* If yes, what do you think the different fields would be on each type?
* It’s also mentioned that pages should be “taggable” -- in what way? 

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSeemz2gd88iKLSU92MZck-kRtH_YqLEIinGXAIM8vHpwgNu7w/viewform?usp=sf_link" target="_blank">Answer Pages questions 🤔</a>

## Events

NDSU Ag & Ext will need an Events content type with the ability to add date-and-time-based events, and present in a list or calendar format. They will also need the ability to offer online registration for an event. Examples from current site(s): https://www.ag.ndsu.edu/info/cal.

* See related events questions in [Open questions](/questions)

## News/News columns

Our understanding is that all news will come from central services and that we may need one or more content types to accomodate news imports. 

* See the related news questions in [Open questions](/questions)

## Profiles

NDSU Ag & Ext will need a Profiles content type. This currently exists on a 3rd party “people” application and needs to be integrated with the new Drupal site. 

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSe4H18_hvVzSWaDJqumoCKRRTtbzbfnr6Uc9PXmhgYW2zqUsQ/viewform?usp=sf_link" target="_blank">Answer Profiles questions 🤔</a>

## Programs

This is a content type for Extension programs and includes event information, registration information, and description text.  Examples from current site(s):

Field to Fork (event)
Pesticide Training (course)
Master Gardener (course)
Spring Fever (event)

See: [Content type desc](https://docs.google.com/document/d/1hibGF9EzPqhJCrmshdzR_hkgxfOv7AMqAowXX1L6AFk/edit)

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSeg1Y19aDgB_EziPfvRqDl1K61CCF9PIwSsyQz1djogod1eyA/viewform?usp=sf_link" target="_blank">Answer Programs questions 🤔</a>

## Publications

NDSU Ag & Ext will need a Publications content type long-form articles with a table of contents. 

See: [Publications](https://www.ag.ndsu.edu/publications)

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLScnIhljl8_cvcfeqJrm5ZdBXzlZu1Ja2jTr4QrdTNjlW7BRXA/viewform?usp=sf_link" target="_blank">Answer Publications questions 🤔</a>

## Alerts

These are banners that appear when needed for emergencies or other important and timely events. Site admins can create these and then choose to publish them. They could appear sitewide at a designated location (typically near the top of the page), or they could be specific to certain sections of the site (e.g. Soybean page has an aphid alert).

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSfWNyurv8IEveBenAa5e0XcxL5YEAjm12YsEJ6HIxU__0uNpQ/viewform?usp=sf_link" target="_blank">Answer Alerts questions 🤔</a>

## Recipes

Currently recipes are simply content in the body field of a basic page, but it is recommended that a new content type be created for specifically for these.

Examples from current site(s): 
https://www.ag.ndsu.edu/food/recipes/beans/black-bean-chocolate-cake

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSfWNyurv8IEveBenAa5e0XcxL5YEAjm12YsEJ6HIxU__0uNpQ/viewform?usp=sf_link" target="_blank">Answer Recipes questions 🤔</a>

## Podcasts

The document mentions podcasts with the ability for people to manage subscriptions. This likely means a dedicated content type with views.

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSfAdWnBf3XWSDvuyWEf4WQnKfzgVs5lPAw7QByKj-iaQIok4g/viewform?usp=sf_link" target="_blank">Answer Podcasts questions 🤔</a>

## Plants

This is a content type for a plants database. It currently exists as a Plant Selector. We plan to duplicate this functionality as is.

Examples from current site(s): 
https://www.ag.ndsu.edu/tree-selector

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSfTY8HycwfuKwoW7JB73UY5ssDCGwUhtUHzhtTdjexondF2LQ/viewform?usp=sf_link" target="_blank">Answer Plants questions 🤔</a>

## Research Reports 

We are unclear on this content type: 

> REC content that has not been Extensionized, is not clearly actionable

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSeoTQIFLKKgjpVo-F2TEquRSBXfwSl9OIyUV7wgvZQOCchnoQ/viewform?usp=sf_link" target="_blank">Answer Research Reports questions 🤔</a>

## Extension County Offices

There are 53 of these currently that appear to function as “microsites” and appear under Extension in the site’s navigation. Content includes, basic  information, resources, staff information, and news. It is unclear at this point if the same approach is expected on the new site.

Examples from current site(s): 
https://www.ag.ndsu.edu/extension/county-extension-offices
https://www.ag.ndsu.edu/casscountyextension

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSe_U_STM14R6Pe9Imcwkh_NfKnb_C9fW5E3BgpsTR_WT3Hr8Q/viewform?usp=sf_link" target="_blank">Answer Extension County Office questions 🤔</a>

## Research Extension Centers

Currently there are 10 Research Extension Centers and currently each is treated like a microsite with it’s own navigation. Content includes pages detailing various research, news, reports, and staff directories. The homepage highlights content found in various sections of the site. Content overall is very file-heavy (lots of links to PDFs). In the new site, these center sites live navigationally under the Ag Hub. It is unclear at this point if the same approach is expected on the new site.
Examples from current site(s): 

https://www.ag.ndsu.edu/research/research-extension-centers
https://www.ag.ndsu.edu/CentralGrasslandsREC

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSfdvxBSlALZeIcdsl_pB4Ij9pUQdqo5ssYlmQPiUaaZ9I5VoQ/viewform?usp=sf_link" target="_blank">Answer Research Extension Centers questions 🤔</a>


## Other

* Videos (Drupal media)
* Images (Drupal media)
* Social media (how to handle, just icon links? share links?)
* Newsletters -- managed externally, subscribe links added to Drupal on relevant pages. Also, an overally landing page? This may need to be a content type, if so. 

See question regarding newsletters in [open questions](/questions)

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSd_3hJuAcYjixdydyPQ168RZIVJ7oC9uOrw58gfmsOp7h0ygQ/viewform?usp=sf_link" target="_blank">Other questions 🤔</a>

## Careers

This is a content type for job postings.
Examples from current site(s): 
https://www.ag.ndsu.edu/careers/current-job-openings

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLScgMay_bLDvyMyPI7-b4lNry_J4cVPLV3p_tvI1nctJyqS8SQ/viewform?usp=sf_link" target="_blank">Careers questions 🤔</a>

### Out of scope for now?

These are all items that were unknown prior to our initial discovery and our initial proposal; we are willing to discuss as needed but given overall project scope, budget, and timeline feel these are best left for a phase two.

* Worksheets/checklists
* Quizzes
* Data vis/interactive tables

See: [Primary Content Types](https://docs.google.com/document/d/1wYS2346FsuRB856vs30HUkO2SYo0NFyIxlIHHQHSlx4/edit#heading=h.a8xanigqye1j)








