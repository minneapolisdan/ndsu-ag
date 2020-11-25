---
layout: layouts/home.njk
title: Project overview 
date: 2020-11-25
permalink: /
eleventyNavigation:
  key: Home
  order: 0
---
The following sections outline our understanding of current project scope, informed by all of the documentation and information generated to date. These documents include the original RFP, questions and responses, Electric Citizen's original proposal, meeting notes, and all files provided by NDSU.

There are still numerous unknowns and questions to be answered and this project overview can be used to both inform those answers and to develop a final techincal architecture. The purpose of this living website is to clarify key technical requirements, and to ultimately create an official build plan.

All the pages in this site are interspersed with "answer" buttons that will open up a Google form allowing you to provide answers to our specific questions. Please be as expansive in your responses as possible; we can set up a Zoom to discuss finer points as needed. (*Note: you will be able to go back and edit or add to your responses as needed.*)

## Primary goals and requirements

Electric Citizen will develop a single Drupal 9 website that will bring the content from numerous areas throughout NDSU ag under a single umbrella. The homepage of the website will consist of a yet-to-be-determined set of content, and from the top level navigation of this website, a user will be able to navigate to one of these main areas and its subpages: 

![Diagram](/static/img/ndsu.png)

* All sections of the main site will share a common theme
* All sections will share a common set of content types and functionality (with limitations and restrictions as needed) 

### 1. NDSU Ag and Ext homepage

We have not discussed the homepage in any detail so we should start this discussion soon.  

**Questions:**

* Is the above diagram accurate, as a high-level overview of how content will be organized on the new site?
* Have you given any thought to how the homepage will be organized?
* What content or types of content should it contain? What calls to action? 
* Will the homepage need any special features or controls different than a standard landing page?
* Is VP of Agricultural Affairs simply a link out to another part of NDSU site?

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/1N26zqAp2S3jSr1kweZHWXhEeTUDFh0PeP0M6GUjO2Fo/edit?usp=sharing" target="_blank">Answer NDSU Ag homepage questions 🤔</a>  

☝️ This will open a response form in a new tab, you can edit/change your responses if needed.


### 2. College of Agriculture, Food Systems, and Natural Resources (CAFSNR)

All of the content for CAFSNR (including general info, all academic programs/units, schools, colleges, etc) will be moved into the new site. This content currently resides here and is quite broad and deep:

https://www.ag.ndsu.edu/academics

All of the departments and schools are currently on two disparate systems with different navigation and content. 

* https://www.ndsu.edu/agecon/ (e.g. Typo 3)
* https://www.ag.ndsu.edu/plantpath/ (e.g. Ag CMS)

Moving forward, all of these sites will be moved under the CAFSNR umbrella of the ag site, with consistent navigation and content types for all units/schools (About, Future Students, Current Students, Faculty & Staff, Alumni, Research, News/newsletters, alerts).

All content and design decisions in this section should be geared toward student recruitments.

#### Questions:

* Does each school/dept have their own content team? 
* Plus a main content team for CAFSNR?
* You mention consistent menus for each school -- does this mean no custom pages/menu items for each school? Or should they be able to add additional pages as needed?
* How should we handle the long name (College of Agriculture, Food Systems, and Natural Resources) in the top-level menu?

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSctQWd81uo58r3nXdCm9zk2USnY5Uw0__v587qQlJNt2pUS2w/viewform?usp=sf_link" target="_blank">Answer CAFSNR questions 🤔</a> 

### 3. Ag Hub

> The goal of the Ag Hub is to provide a one-stop source for information about various ag topics (for example, wheat production, federal ag programs, variety trials, farm/ranch stress) rather than content stored based on organizational structure (on departmental, REC, etc. websites).

#### Questions: 

The Ag Hub is a new top-level section of the website that will be used to organize content that is currently spread across numerous different websites including Extension, AES, and CAFSNR. Paulsen is currently developing the list of content and an architecture for this content, and have produced an initial wireframe. 

* [Content architecture](https://docs.google.com/spreadsheets/d/13ONJKXYxq10thkYPBgB92lCRoIgG1FVTbxRyoc6xThk/edit?usp=sharing)
* [Wireframe](https://www.figma.com/proto/HmJmEmT8DQyGhk6Do370rn/NDSU-Wireframe?node-id=9%3A51&viewport=176%2C-201%2C1&scaling=min-zoom)

::: callout 
*This remains the most unclear part of the project for our team.* Our understanding is that it will contain a mixture of new content, along with content pulled from both Extension and perhaps CAFSNR. Defining the Ag Hub needs to happen soon and will inform large parts of the architecture.
:::

<!-- **Questions:**  -->

* From our conversations and from the wireframe presented, it appears this was originally intended to be a stand-alone site, but is now being folded into this umbrella site. Is this correct? 
* From a technical level, this appears to mostly be a topic-based directory that includes search in order to present a variety of content (and content types) in a one-stop section of the website. Is that correct?
* Given that this is no longer a stand-alone site (assuming our assumption is correct), **we believe there may be a better approach to the Ag Hub that is structed more like a searchable directory of resources (perhaps with faceted search), instead of a "minisite" within a site**. Are you open to discussing this approach?
* In the architecture linked above there is a lot of content listed for Ag Hub that is actually part of extension, or another area of this site. 
* We need to best determine how Ag Hub will function to pull in that content, vs creating it two places.
* In your site outline, you have both county centers and research centers under Ag Hub, while we are envisioning them under Extension, with CONTENT from those centers pulled into the Ag Hub as appropriate.
* You site map also does indicate other content, such as all of the topics shown in the wireframe -- only REC/AES -- is your current thinking around Ag Hub much simpler than we are envisioning?

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLScR2wn1BZPV3PXiqwxceIJJDfAenxCDQuCbfV93gyWr6LzBhA/viewform?usp=sf_link" target="_blank">Answer Ag Hub questions 🤔</a> 



## 4. NDSU Extension

All of the content from NDSU Extension will be moved over to the new site and available via top level navigation. The content for extension can currently be found here and is also quite broad and deep:

https://www.ag.ndsu.edu/extension

There are subsites for each primary area of extension (e.g. Crops, Farm Economics) that contain:

* **Topics** -- these seem to be variety of pages and sub-pages within each area that contain everything from publications and PDFs to subpages to external links etc. They appear to be organically organized and created (and many are out of date.)
* **Programs** -- multiple programs per landing page, each with its own subpages. Links to external registration. 
* **Publications** -- a list of linked publications that are pulled from the global publication content type. Clicking a publication takes you directly to the publication section of the site.
* **Connect** -- a page with bio info, headshots, and basic contact info for each area.


Each topic currently has a slider with large images linking out to various places, including Youtubes, links to pubs, etc. There are also links to “apps”, quick links, resources, latest tagged news.


**Questions:**

* NDSU indicates that this content is being re-organized with a new architecture. When will this work be complete?
* Are the "topics" pages all self-managed by each group? They are set up different, and many are out of date.
Is there a better way to handle "topics"? 
* For program registrations, these appear to be handled by an external link to an NDSU payment system -- can we assume this to be case moving forward also?

<a class="button bg-green-500 hover:bg-blue-500 rounded" href="https://docs.google.com/forms/d/e/1FAIpQLSePCUUinA-TxTU_6w7K0pINmIOvFxN9p7udggKaPb9i3XGwEQ/viewform?usp=sf_link" target="_blank">Answer Extension questions 🤔</a> 

## Assumptions and Agreements

* EC will build a single site Drupal architecture, including all of the content types, views, taxonomies, and all other related Drupal configuration in order to build out the site as described above and elsewhere on this project site
* NDSU and/or its partners will be responsible for all content migration into this new platform



