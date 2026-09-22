---
permalink: /
title: "About me"
header:
  image: /title_image.jpg
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Hi! I am Rishabh Ranjan, a Masters student in Astrophysics at the University of Bonn, Germany. I work on topics related to cosmology, particularly galaxy surveys, higher-order statistics and cosmological inference.

How did I get here?
======
_"Since I was a child, I was interested in these twinkling objects in the sky..."_, yeah, maybe this is not the best starting point :)

I did my bachelors in Mechanical Engineering at IIT Bhilai. After doing some coursework in this field, I realized that a lot of skills I learnt could be used in Physics and Astrophysics, particularly fluid dynamics and thermodynamics. This motivated me to explore and pursue university-level physics as a minors specialization during my bachelors. I further propelled myself into some undergraduate research in both of these fields, and found that I was highly inclined towards computational astrophysics and cosmology. 

I graduated from IIT Bhilai in 2023 and started working at Deutsche Bank as a model validation analyst. Once again, I realized that the interplay of markets is modelled the same way as stochastic systems are modelled in physics. These connections between seemingly diverse fields widened my world view (and certainly added some value to my job experience :D). But I wasn't quite satisfied, since I got addicted to working with the physics beyond the skies.

Hence I went ahead to pursue a masters degree in astrophysics at the University of Bonn starting 2024. As a part of my coursework, I got exposed to a multitude of topics in astronomy and astrophysics, the one that fascinated me the most was cosmology. This started my quest for pursuing a research career in cosmology, of which the internship with Prof. Cristiano Porciani on exploring the different dynamical dark energy parameterizations was just a small step in the right direction. I started my master thesis under the supervision of Dr. Alexander Eggemeier and Prof. Cristiano Porciani in Nov 2025 on the topic "Extending the Evolution Mapping to the Nonlinear Matter Bispectrum".

Cool, but what do I actually do?
======
If I have to explain my current research badly, I'd say that I'm working on methods to speeden up the process of "counting triangles in the sky". ;)

If it doesn't ring any bells, don't worry, here's a better explanation: I am working on developing methods to expedite the computation/emulation of the nonlinear matter bispectrum using the evolution mapping framework. Keeping it light, I'd just say that evolution mapping is a technique that reduces the number of cosmological parameters required to accurately estimate the nonlinear matter power spectrum (you can read more about it here: [Sanchez2022](https://arxiv.org/pdf/2108.12710), [Sanchez2025](https://arxiv.org/abs/2511.13826)). My work extends this framework to the nonlinear matter bispectrum. 

Throughout this project, I have learnt how to deal with N-body simulations, generate overdensity field grids, estimate bispectrum from simulations and use Gaussian process to build fast and robust emulators.

Is that the only cool thing I did?
======
Maybe not :)

During my internship with Prof. Cristiano Porciani, I explored different dynamical dark energy models (or parameterizations) and tried to investigate in detail whether the choice of functional forms affects the constraints on the dynamical dark energy parameters w_0 and w_a. Long story short, it doesn't. Through this project, I learnt how to perform cosmological inference, which is a very important skill to have in cosmology. I also learnt how to deal with cosmological codes written in Fortran such as CAMB (despite my reservations against this extremely outdated language).

Besides cosmology, I also jumped into the realm of Magnetohydrodynamics (MHD) simulations. I started an internship with Prof. Jennifer Schober on exploring the phenomena happening before the onset of kinematic phase in nonhelical forced MHD systems. This project provided me with an opportunity to put my knowledge of fluid dynamics and simulation skills to use, while teaching me more about the statistical methods of studying turbulent systems.

What about interests beyond academic pursuits?
======
Besides my academic endeavours, I love making and mixing EDM songs. Till now, I have made 100+ EDM mashups (not public yet) and will be doing more. Furthermore, I love reading comics, mostly by the likes of Marvel and DC. I can have a conversation on Jonathan Hickman's Secret Wars storyline for hours, and it seems that Marvel Studios is also taking that route in their movies, so a big win for me!

<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template! -->

 <!-- You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads! -->

<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
