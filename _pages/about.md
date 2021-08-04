---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi! I am Tianli Pan, a PhD student at Hong Kong University of Science and Technology, supervised by [Prof. Charles W.W. Ng](https://charles-ng.hkust.edu.hk/) and [Prof. Bo Huang](http://www.iseis.cuhk.edu.hk/zh/huangbo.html). I currently work in the Areas of Excellence (AoE) Project for establishing a world-leading [Centre for Slope Safety](https://slope-aoe.hkust.edu.hk/), and my role in this project is to utilize both Unmanned Aerial Vehicle (UAV) and satellite images to develop algorithms for vegetation classification and the landslide detection.


Education
======
2021.09-present         Ph.D in Civil Engineering, School of Engineering, Hong Kong University of Science and Technology.  
2017.09-2020.06         M.S. in Cartography and Geographical Information Sytem, Faculty of Geographical Science, Beijing Normal University.  
2013.09-2017.06         B.S. in Geographical Infomation Science, College of Earth and Environmental Science, Lanzhou University.

My work and Research
======
I’m a disciplinary nomad, integrating disciplines like computer science, information science with fields like geography and sociology. Methodologically, I am trained as a qualitative geographer, spending a lot of my time in exploring using computer algorithm to understand the both physical and social geography phenomena. My past research experiences involve using DMSP satellite images to provide detailed map of pixel-level population density distribution, calculating river discharge through UAV and multi-spectral satellite images and monitoring landslide with 3D laser. Through my research experiences, I have commanded using qualitative, quantitative, and computational methods to process geographical data. use statistical forms of analysis to contextualize and further support more qualitative approaches, frequently collaborating with people from other disciplines

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
