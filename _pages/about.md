---
permalink: /
title: "Always think outside the box"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
------
I am Di-Ao Liu, a 6th year graduate researcher and cell biologist in the [Department of biology at UPenn](https://www.bio.upenn.edu/). I have been studying extracellular vesicles, membrane trafficking, artificial cell culturing system, and omics in a research lab supervised by Prof. [Wei Guo](https://www.bio.upenn.edu/people/wei-guo). 

My rearch focuses on the understanding of basic cell biology underlying the biogenesis of exosomes. Specifically, I focused on (1) The exocytic factors that turns MVEs (multivesicular endosomes) to secretory organelles as exosomes. This has been listed as a key questions in the field of extracellular vesicle [Box1 Qline3 & 4](https://www.nature.com/articles/s41580-022-00460-3). We proposed a mechanism that the subpopulations of MVEs [switch their phosphoinositides](https://www.nature.com/articles/s41467-023-42661-0) to recruit exocytic factors such as Rabs and exocysts. (2) The exosome biology in the tumor microenvrionment and the response to [mechanical cues](https://www.nature.com/articles/s41556-023-01092-1). This study reveals that the stiff ECM (extracellular matrix) of the liver tumor is an environmental cue to promote the release of exosomes and the activation of the NOTCH signaling in tumors. The work has been highlited in the top of the Nature collection list of ["Extracellualr Vesicle" basic mechanisms](https://www.nature.com/collections/hjjfdgedbg) and provide an answer to another key question about ECM-Exosome crosstalk [Box1 Qline2 & 5](https://www.nature.com/articles/s41580-022-00460-3). 

I rotated with Prof. [Hongjun Song](https://www.med.upenn.edu/songlab/) and performed scRNAseq studies of brain tumor organoids in parallel with their primary tumors as reported in [Cell](https://www.med.upenn.edu/songlab/assets/user-content/documents/Cell_Dec2019.pdf). 

I received my B.S. degree in Biology from [School of Biology](https://lifesciences.sysu.edu.cn/) and Yat-sen School [Top Scientist Plan](http://en.moe.gov.cn/features/PressAndInterview/Pressreleases/202001/t20200117_415852.html) at SYSU as advised by Prof. [Jun Cui](https://www.researchgate.net/profile/Jun-Cui-10). 






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
