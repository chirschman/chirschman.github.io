---
permalink: /
title: "Hi there!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Caelyn, a biomechanics researcher completing my PhD in Dr. Alena Grabowski's Applied Biomechanics Lab at the University of Colorado Boulder. I am passionate about assistive devices, footwear and product development. My PhD work has been focused on using biofeedback to aid with gait retraining in somebody with an amputation, applying the mechanics of biolological legs when running on slopes to future assistive device design, product testing for Specialized and investigating performance differences between women's specific and mens soccer cleats when worm by female soccer players.

My Work and Research
======
My masters work was focused on quantifying the mechanics of the biological leg when running on uphill and downhill slopes to apply to future assistve device design. Athletes with a unilateral trans-tibial amputation use a running specifiic (RSP) prosthesis to run. These devices are designed to mimic the mechanics of the biological leg when running on level ground. The mechanics of the biological leg have yet to be explored when running on slopes and could be benificial when designing a versitile RSP. We quantified joint stiffness of the ankle and knee and used a novel equation to calculate how the ankle and knee contributions to overal leg stiffness change on sopes compared to level ground. To see what we found, see the publications tab!

My PhD work has been focused on investigating how real-time visual feedback of peak propulsive force effects the biomechanics and energetics of an individual with a unilateral trans-tibial amputation when using an Energy Storage and Return (ESAR) propsthesis compared to the BiOM powered ankle-foot prosthesis. With mixed results in the literature reagrding whether the BiOM can normailze biomechanical compensations and elevated metabolic cost that we see in this popuation, further investigations are needed to see whether training can help individuals utilize the push-off power provided by the BiOM. Stay tuned to see what we find out about this!

A PhD wouldn't be complete with a handleful of side projects. I have helped Specialized test their 3D printed saddles and attempeted to improve the repetability of EMG electode placement. I have also helped out with a project that is comparing the gold standard method of motion capture to IMU's when mesauring the angle changes that occur when a prosthetist changes the alignment of a prosthesis. I am also interested in how female specific soccer cleats effect performance of female soccer players compared to when they wear mens cleats.

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
