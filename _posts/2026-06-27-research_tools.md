---
layout: post
title: Beginner's Tools for Research
date: 2026-06-27 01:14:00
description: Research tools I found useful as a beginner.
tags: zotero zettlr python research cite automation 
categories: research
giscus_comments: false
related_posts: true
toc:
  sidebar: left
---
While getting into research the first thing that overwhelmes most is the literature survey. Initially it might seem like never ending. Each article will cite plenty of other articles to read for an overall understanding. Eventally it can be a real stuggle to keep track of what you have read and find a specific article in your mind. 

Over time you might remember keywords and images to search the article for digging the details. 
One good way to keep track of an article is to write a line or two about it under a broader topic and cite it. You can do it in a notebook/diary but with increasing number of articles and topics it might be difficult to navigate. 
Another thing is when you are discussing with someone you may have your computer infront of you rather than the diary for a quick search. Then if you want to write and share something it is 99% times digital so it might be faster if you have already something written digitally. Although nothing can beat pen and paper while connecting ideas or resolving complex queries.

During experiments you will generate a lot of data repeatitively, processing and visualizing them manually (Excel-Origin way) can be fustrating. You will get addicted to automation and workflows for faster understanding of data and be less boared once get used to writing codes/scripts. 

In this context I will give a glimpse of three free tools I found very useful while starting as a PhD student - 
- [Zotero](https://www.zotero.org/) - for collecting, navigating and citing articles
- [Zettlr](https://www.zettlr.com/) - for writing, conslidating topics with citations and cross referencing
- [Python](https://www.python.org/) and [VS Code](https://code.visualstudio.com/) - automating data processing and visualizations.

### Zotero
‘[Zotero](https://www.zotero.org/) is a free, easy-to-use tool to help you collect, organize, annotate, cite, and share research’. When you get a relevant paper just copy the doi and enter in Zotero, it will automatically fetch all details of the paper and if possible also the pdf in the Zotero library. You can have different libraries in Zotero for different research topics. 

The features I find attractive in Zotero -
- adding new papers just by entering DOI
- exporting citations for latex
- citing directly in MS Word
- integrated search bar
- intergrated pdf reader with higligting and note
- tagging
- RSS feeds for getting journal research updates
- auto update exported bib file with [BetterBibTex](https://retorque.re/zotero-better-bibtex/index.html)
- visualizing connection between the atricles with [Cita](https://github.com/zotero-cita/zotero-cita)
- multi device sync with account (but limited storge)

<div class="row mt-3">
        {% include figure.liquid loading="eager" path="assets/img/blog/zotero_add_item.webp" max-width="90%" class="img-fluid rounded z-depth-1 mx-auto d-block" zoomable=true %}
</div>
<div class="caption">
    Adding citations in Zotero
</div>

<div class="row mt-3">
    {% include video.liquid path="https://www.youtube.com/embed/mxLdFJoaFBY?si=QWrYfWRstvf-vGSM" class="img-fluid rounded z-depth-1" %}
</div>

For getting more detalied use cases go through the [Zotero documentation](https://www.zotero.org/support/quick_start_guide)

-> [Better BibTeX (Zotero Plug-In) - LaTeX - LibGuides at University of Massachusetts Amherst](https://guides.library.umass.edu/c.php?g=1402580\&p=10705039)\\
-> [Wikidata's Cita page](https://www.wikidata.org/wiki/Wikidata:Zotero/Cita)

### Zettlr
While wrting in MS word, manging documents more than a few pages with figures and equations becomes fustrating. So, we go to latex for peaceful writing in a text editor and less bothered about the postions or numberings and finding symbols for equations. But in latex you need to compile the document you have written everytime you want to see the final result. While just jotting down a draft it might feel a lot of work and you go back to word. [Markdown](https://www.markdownguide.org/getting-started/) comes as a saviour with very minimal writing syntax but works like a live latex document. There are different markdown flavours available with few variations in syntax. 

For jotting down connected topics or ideas, and also writing aricles for publishing, [Zettlr](https://www.zettlr.com/) is a tool of comfort. Interstingly, whatever you write in Zettlr you can export to pdf, Word, latex, html and so on. It can serve as a primary drafiting station. Citations, equations, links, images, videos, tables, lists anything at ease. This page itself is written in Zettlr.

<div class="row mt-3">
    {% include video.liquid 
    path="assets/video/zettlr_eqn.mp4" 
    class="img-fluid rounded z-depth-1" 
    autoplay=true 
    loop=true 
    muted=true 
    playsinline=true 
    %}
</div>
<div class="caption">
    Writing equation and symbols in Zettlr
</div>

Using a bibliography source file loaded you can seamlessly add citations inline - 
<div class="row mt-3">
    {% include video.liquid 
    path="assets/video/zettlr_cite.mp4" 
    class="img-fluid rounded z-depth-1" 
    autoplay=true 
    loop=true 
    muted=true 
    playsinline=true 
    %}
</div>
<div class="caption">
    Adding citations in Zettlr
</div>

<div class="row mt-3">
    {% include video.liquid path="https://www.youtube.com/embed/OPQDX6d3hjk?si=5FcfSx0XFTN0j12B&amp;start=145" class="img-fluid rounded z-depth-1" %}
</div>

Visit [Zettlr documentation page](https://docs.zettlr.com/en/) to explore the possibilities.

-> [Basic markdown sytax](https://www.markdownguide.org/basic-syntax/)\\
-> [Zettlr citations documentation](https://docs.zettlr.com/en/editor/citations/)\\
-> [Zotero and Zettlr integration](https://docs.zettlr.com/en/guides/reference-manager-integration/#)\\
-> [pandoc-crossref releases page](https://github.com/lierdakil/pandoc-crossref/releases/tag/v0.3.24a)

### Python and VS Code
As

