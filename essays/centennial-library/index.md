---
# Change these five lines as soon as you copy this starter.
title: Centennial Library
author: Khoa N
category: Student Resource                  # change to a category from the student guide
header-image: Library - Centennial Science and Information - above-ground entrance.jpg   # the filename of your own image
header-caption: New Mexico Digital Archive

# Fill these in later, once your research is under way.
card-description: Replace this with two sentences that summarize the story your essay tells and why it matters.
start:                                   # the year your story begins, shown on the map

# Leave this line as it is.
layout: essay
---

This first paragraph should give readers a quick way into your topic. Start with a scene, a question, a surprising fact, or a problem your essay will explain. You do not need to summarize everything here. Help the reader understand why this campus place, person, organization, object, or event deserves attention.

Keep the above lead paragraph first. Do not put an image, a heading, or any other component above it.

## Main Story

The Centennial Science and Engineering Library (CSEL) at the University of New Mexico in Albuquerque has served students, faculty, and researchers in science, engineering, and mathematics since the mid-1980s. Its history reflects the changing role of academic libraries, from providing specialized books and printed journals to supporting computer-based learning, digital research, and interdisciplinary collaboration.
Origins and early development, 1985–1996
The library’s origins date to approximately 1985–1986. The University of New Mexico’s Department of Electrical and Computer Engineering reports that its new building was completed in 1986, with the library occupying part of the building’s two-story underground area. The department marked the building’s completion with a ribbon-cutting ceremony that used a laser. Although these records establish the library’s approximate beginnings, they do not provide an exact opening date.

During the 1990s, Centennial increasingly incorporated computers into its educational services. The university’s 1995–1996 annual report describes the development of an electronic classroom and improvements to the Electronic Information Access Center, supported by two grants from Intel Corporation. The report records that 1,115 students attended 129 library instruction sessions during the 1995–1996 academic year. Librarians helped students learn to locate and use information, while the library expanded its electronic research services.

An especially revealing event occurred in 1996, when library staff placed a time capsule inside a wall during construction. The capsule contained paper documents describing library services, including information about contacting staff by email. According to UNM News reporter Karen Wentworth, Centennial was the first library on campus to begin using email. Staff deliberately preserved materials that were part of their everyday work, creating a record of a technological transition that seemed significant enough to commemorate.

By the 2003–2005 academic years, Centennial had developed substantial research collections. The university’s catalog documented approximately 300,000 volumes of books and journals, 1.6 million microforms, and 1,800 current print journal subscriptions. Its Map and Geographic Information Center (MAGIC) held more than 200,000 maps, images, aerial photographs, and other geographic resources. The library’s two underground levels provided seating for more than 800 users. These figures illustrate the scale of the specialized resources available to the university community.

On June 22, 2010, UNM librarians Martha Bedard and Johann van Reenen presented The e-research center: transforming a traditional science library at the International Association of Scientific and Technological University Libraries conference. Their presentation described a year-long planning process involving faculty, students, and library staff. They proposed developing an eResearch Center that would support scientific computing, data-intensive research, visualization, collaboration, and research-data management. The presentation is evidence of the library’s planned direction, rather than proof that every proposed feature was subsequently implemented.

On May 5, 2012, a mechanical-room fan failure triggered the fire-suppression sprinklers, causing water to flow into the library’s lower level. Some maps in MAGIC were damaged, and 65 map cabinets were found wet or damp. University staff arranged for the affected maps to be inventoried and sent for freeze-drying and conservation processing.

Later that year, construction crews renovating Centennial to accommodate a new Math Learning Lab uncovered the time capsule installed in 1996. Wentworth reported the discovery on December 12, 2012, connecting the library’s earlier adoption of email and computers with the continued evolution of its learning spaces.

A more recent addition combined the library’s academic mission with student creativity. On September 7, 2023, UNM presented a hallway mural by Esther Elia, a recent graduate of its Master of Fine Arts program. Selected through an open call to UNM student artists, Elia’s design draws on Assyrian, New Mexican, and Iranian cultural influences. The project added a public work of art to the library’s lower level.

Today, Centennial continues to provide collections in science, engineering, and mathematics, alongside maps, anatomical models, and reservable study rooms. Its history shows how a specialized university library has adapted to changing research technologies while continuing to support learning and discovery.

<!-- Full-width figure. This is the default for any landscape photo wider than about 700px.
     image-path is just the filename: upload your images into this essay's folder,
     next to index.md. -->

{% include images/figure.html
  class="img-center"
  width="100%"
  caption="Replace this caption. Say why the image matters, not just what it shows, then cite where you found it: [Center for Southwest Research](https://econtent.unm.edu/), collection and box number."
  image-path="sample-archive-photo.jpg"
%}

Every image needs a caption, including this one. A caption should explain what the reader should notice and where the image came from. Captions accept Markdown, so use `[source](https://example.com/)` to link to a digital collection whenever the image has an online home.

## What Changed

Use this section to explain change over time. What did your topic used to be? How did people use it, describe it, fund it, argue about it, rename it, neglect it, preserve it, or forget it?

This is a good place to connect your specific topic to a larger campus pattern: enrollment growth, architecture, student life, race, gender, labor, protest, public memory, administration, technology, or access.

<!-- Carousel: use when you have three or more images that belong together but do not
     each need their own paragraph. Images are split on commas, captions on the | character.
     Carousel captions are plain text: Markdown links will NOT work here, so write out
     the collection name and box number instead of linking. -->

{% assign images =
"sample-archive-photo.jpg,
sample-second-photo.jpg,
sample-primary-source.jpg" | split: ','
%}

{% assign headers =
"Replace with a short slide title,
Replace with a short slide title,
Replace with a short slide title" | split: ','
%}

{% assign captions =
"Replace this caption. Explain what this slide shows and why it matters. Center for Southwest Research, collection name, box number.|
Replace this caption. Every slide needs one. Center for Southwest Research, collection name, box number.|
Replace this caption. Plain text only in carousels, so spell out the source instead of linking. Center for Southwest Research, collection name, box number." | split: '|'
%}

{% include images/carousel.html
  images=images
  headers=headers
  captions=captions
%}

Delete the carousel if you do not have a set of images that works this way. Three related photographs, a series of floor plans, or a run of newspaper clippings are all good candidates. Two images that need to be compared directly are usually better as a pair than as a carousel.

## Evidence

Use this section to show readers a document, not just a photograph. Scanned letters, meeting minutes, ledgers, clippings, and blueprints all reward close looking, and they prove you spent time in the boxes.

<!-- Portrait documents are the exception to the full-width rule. A tall scan at 100%
     is over 1200px tall and swallows the screen, so center it and leave it near 55%.
     Keep it centered, not floated. -->

{% include images/figure.html
  class="img-center"
  width="55%"
  caption="Replace this caption. Tell readers what to notice in the document and why it changes how they should understand your topic. Cite the collection, box, and folder."
  image-path="sample-primary-source.jpg"
%}

Explain what the document says, what it does not say, and how it fits the story. A source you actually read and explain is worth more than three you only mention.

## Why This History Matters

End by returning to the present. How should readers see this campus place, person, organization, object, or event differently after reading your essay? Point to continued use, memory, loss, gaps in the archive, or campus change rather than announcing a conclusion.

{% capture bibliography %}
- Replace this with your first source. Include enough detail that someone else could find it: collection name, box, and folder for archival material.
- Replace this with your second source.
- Replace this with your third source.
{% endcapture %}

{% include typography/bibliography.html
  title="Bibliography"
  content=bibliography
%}
