---
title: Open questions (high level)
date: 2020-11-20
permalink: /questions/index.html
eleventyNavigation:
  key: Open questions
  order: 3
---
These are a variety of high-level topics for open discussion that will inform some significant architectural decisions. 

## Navigation questions

Navigation on a large Drupal site with many editors and several distinct sections can get quite complex, and we hope to find a simple efficient way to handle menus. 

* In an ideal world, how will top level and sub navigation be handled? 
* e.g. If I go into the CAFSNR or Extention areas of the site, should there be a second-level of horizontal navigation at the top? Or in a sidebar? A megamenu?
* Presumably the top-level will also include some links to global "news", "events", "contact" etc.  
* Within a subsection of the main site, should this global nav always appear? 
* Will there be one person/office responsible managing the main navigation? 
* Who else needs the ability to add their OWN pages/items to the navigation? (e.g. Research centers, extension groups)

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSek60Fsqi2DSxYL_giop0AcX8nGC2oAl_52Ow1dA_yi1t4YDA/viewform?usp=sf_link" target="_blank">Answer Navigation questions 🤔</a>

## Content sharing throughout site

> Educational content produced at the county level should be integrated into the appropriate topic area on the Ag Hub or Extension sites.

This is one of several examples where NDSU mentions content flowing into the Ag Hub, or from one area of the site to another. (e.g. Publications)

* In Drupal, content has a single home or source of truth
* We can pull in content via relationships/tags, but it will always live in a single place
* For example, a Publication will always be a node that lives in the Publications area of the site
* But based on tags, we could then show that publication on the relevant page of the site

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSdlJgP-C06W3n_du0FI6gbwZJeAfMA-LJLzoEaSU8ivt6UVTw/viewform?usp=sf_link" target="_blank">Answer Content sharing questions 🤔</a>

## Events

We will likely have more questions surrounding events as we go but here are some to start with, so that we can begin planning a bit more how these will work.

* We need more clarity on event "series", events with "multiple locations"
* As noted we did not plan for or budget a full-scale event registration system -- can we assume that we can rely on external links to the NDSU payment system as in place now?
* We also need more clarity on how "programs" (within Extension) will relate to events? Do "programs" need to show up in the main event calendar?

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSepFTSyadDrvInL2J8mjj6DFypsInpGCWZQKHyeiNhbj5Mngg/viewform?usp=sf_link" target="_blank">Answer Events questions 🤔</a>

## News

We are unclear about the specific content types needed for "news releases" and "columns" and/or "new alerts" content type, or whether all of the news will be coming directly fromn Central Services (Plone).

Examples from current site(s): 
* https://www.ag.ndsu.edu/news/newsreleases/2020/aug-3-2020/inventory-forage-supplies-early/view
* https://www.ag.ndsu.edu/news/columns/spotlight-on-economics/spotlight-on-economics-selfish-behavior-has-economic-costs
* https://www.ag.ndsu.edu/academics/student-profile-billie-lentz

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLScwyp1cxdB565XEpI5zBn-oTNYdCIpS0akCEsWjYOH5dzlsog/viewform?usp=sf_link" target="_blank">Answer News questions 🤔</a


## Publications

Our assumption is that Publications will remain its own, stand-alone area of the website with a single content type, but that publications can also be linked to elsewhere within the site. (e.g. if a college or program has a "publication" a description and link can be pulled into their pages via a tag view).  Publications will also be pulled into the Ag Hub (we think?) again via a tagged search or view. 

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSdip5gbulPf9VFpJHDfgWzZnTZwHBf6MiDUTn9HpBJX2yfAzA/viewform?usp=sf_link" target="_blank">Answer Publications questions 🤔</a>



## Group module, Workbench Access, Content moderation

We need to develop more detailed requirements surrounding each of these areas to determine appropriate user roles, workflows, and methods. These decisions will have a significant effect on overall site archicture. 

* **Group** -- this module may be a candidate for letting research centers and county sites manage their own content and menus. 
* **Workbench Access** -- this is a third-party module that helps us control who can edit what content and provides a fairly reasonable way to manage access across a wide range of content. We are considering this as the main candidate to manage content within CAFSNR, Extension, and Ag Hub. 
* **Menu access** -- one big issue in Drupal is menu permissions; if you give a user permissions to manage menus they typically have access to manage ALL menus. This usually undesirable so we will need more details surrounding expectations for menu management
* **Number of menus** -- we'll need to determine whether we create separate menu structures for each key area of the site, or rely largely on one main menu

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSdZE3bzAOGK8-gykPvoPLQVJIooEyN3qrBl8_IkuWbUP13Kug/viewform?usp=sf_link" target="_blank">Answer workflow questions 🤔</a>

## Content syndication

As noted in the overview, content from Central Services will be pulled into this website and we noted a number of concerns and questions. We will call them out here again as they are of special concern:

* How will we be accessing this data? 
* Is there a documented API for each, or a feed of some sort?
* What type of data will we get in response? (JSON, XML, ?) 
* Are we able to query the data? (e.g. query news by department, or topic -- query directory by department)
* NDSU notes the directory will need to be expanded to include AES/CAFSNR -- when will this work be completed?
* What documenation is available for accessing these services? 
* Does every department/group etc. have a newsletter? How many are there? 
* We need to determine best way to integrate these in a flexible way throughout as needed

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSeIxUIoHBoV7iO84mIyoc3sMdtCuGuct_A9gZ2sgRQp_4VoFw/viewform?usp=sf_link" target="_blank">Answer Content syndication questions 🤔</a>

## Tools

In previous discovery we identifed two main JS tools (e.g. Wheat nitrogen calculator), and list of Excel spreadhseets used as tools. Our current plan is to re-theme and hopefully use the exact JS in the current tools, and to link to each spreadsheet as appropriate. 
 
 See: [List of tools](https://docs.google.com/spreadsheets/d/13ONJKXYxq10thkYPBgB92lCRoIgG1FVTbxRyoc6xThk/edit#gid=996020785)


<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSdFcPaHGKOCyf6MQwipdKwzr2BOj5AZaZV_9rm30nlgADZNSA/viewform?usp=sf_link" target="_blank">Answer Tools questions 🤔</a> 

## Newsletters

To design an effective way to organize newsletter subscribe buttons throughout the site, we need a bit more information. 

* Does every department/group etc. have a newsletter? How many are there? 
* If we build a widget that allows you to drop a "subscribe to newsletter" button, with some descriptive text onto any area of the site is this sufficient? Are the newsletters coded such that the content editor would know what code to use for their particular newsletter?

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSeYlo2fNS5qyZ4WfGyobo6xEQvzjWUIDYyHMBHgeeslKYghhg/viewform?usp=sf_link" target="_blank">Answer Newsletter questions 🤔</a>

## Calls to Action

We have not discussed how, or if, to handle calls to action. Many of our higher ed clients use a standard set of "Schedule a visit!" or "Apply now" or "Contact us" calls to action that can be placed in key places on the site. 

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSfsBsbcUjZ9FCerfYRr-EZFBPSq2MNgWguWLEFJg2VY3bAhYw/viewform?usp=sf_link" target="_blank">Answer CTA questions 🤔</a>

## Search

We have not discussed search; unless NDSU provision a Solr server we will be limited to core Drupal search and search API. This is powerful, but will limit ability to do certain things like searchable PDFs.

* How will search be handled? 
* Global search plus Ag Hub search? 
* Any other key search requirements? 

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSesFsA0odCb8gteIaoatXbjaInn_J2Yhl7HeSHV7-Z-9znLrQ/viewform?usp=sf_link" target="_blank">Answer Search questions 🤔</a>
