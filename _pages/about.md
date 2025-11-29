---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I'm a scientist working at the University of Cambridge. I graduated with a first-class MSci degree in Astrophysics at Royal Holloway, University of London, before completing an MSc by Research in radio astronomy at the University of Hertfordshire. I then continued at Hertfordshire with a PhD in radio astronomy, where I studied the properties of radio galaxies using a variety of modern telescopes, creating some of the first systematically-selected samples of rare populations of radio galaxies. After my PhD, I was a post-doctoral researcher at the Thueringer Landessternwarte in Germany, where I continued my research. In 2023 I joined the Cavendish Laboratory at the University of Cambridge, continuing my work on radio galaxies and also working on the software development of the world's largest scientific ecosystem in the form of the next-generation telescope: the Square Kilometre Array.  

I'm a radio astronomer -- I use radio telescopes to peer through the Universe through many lenses. Specifically, my research revolves around understanding radio-loud galaxies. The radio waves from these types of galaxies far outshine the light coming from all the stars in the galaxy combined. Connected with this scientific research, I most heavily work on software related to processing all these radio signals into maps that tell us about the physics of these objects: radio astronomy is itself a big data problem and innovative software is required in the coming years to help us understand even more about the cosmos. My other academic interests are on the nature of cosmic magnetism, cosmology of the early Universe, and on high energy physics in general. 

If you'd like to know more, please contact me through the links on the left.

Research: radio galaxies shaping our Universe
======
The most massive galaxies in the Universe contain active super-massive black holes -- through accretion of hot plasma including magnetic fields, they launch high-powered beams of charged particles that often escape the galaxy. The combination of charged particles and magnetic fields in these beams or jets releases synchrotron radiation, and we see most of this at radio wavelengths. The radio sky is littered with these so-called radio galaxies, some galaxies having very large and powerful jets and some having small and weak jets, but nevertheless, there is enough power in these sytems to disrupt the normal processes in galaxies such as star-formation. 

I undertake a variety of projects to understand radio galaxies:
- I am principle investigator of a large programme with the Jansky Very Large Array (JVLA) to image and understand the physics of the brightest radio galaxies in the northern hemisphere. This will produce the highest dynamic range maps at 1.5 GHz and 6 GHz of the famous 3CRR sample. Using the new maps with the expected newly detected features such as filaments and faint hotspots, we will re-ignite models for their evolution, to truly understand their role in shaping galaxy evolution. These studies will be complimented by similar maps made at different wavelengths, from 144 MHz to infra-red and X-rays. 
- Using the Low Frequency Array (LOFAR), a highly sensitive telescope operating at low radio frequencies, I map the faint components of bright radio galaxies to understand the physics of the plasma in the low energy regime. In particular, I am interested in X-ray ghosts, which show bright X-ray emission coming from the Cosmic Microwave Background being up-scattered to X-rays from the low energy electrons in the lobes of radio galaxies. This has meant, historically, that we have never seen the radio emission from this plasma because it has become extremely faint. I have now detected this missing radio plasma using high dynamic range images from LOFAR of a handful of objects, shedding light on the interaction between radio galaxies and cosmological structure formation. I plan to undertake a large survey to find all of these objects. 
- [Plotly](https://plotly.com/javascript/) for plotting

Software: processing data from SKA and LOFAR
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Other
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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
