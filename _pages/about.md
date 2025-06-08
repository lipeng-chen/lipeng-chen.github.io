---
permalink: /
title: "Lipeng Chen"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a tenure-track associate professor in the [School of Artificial Intelligence (SAI)](https://soai.sjtu.edu.cn/), Shanghai Jiao Tong University (SJTU). Prior to this, I was a senior research scientist at the [Tencent Robotics X](https://roboticsx.tencent.com/#/), and a research associate advised by [Michael Mistry](https://homepages.inf.ed.ac.uk/mmistry/index.html) at the [Edinburgh Centre for Robotics](https://www.edinburgh-robotics.org/), University of Edinburgh. Before that, 
I received my PhD degree from the Robotic Manipulation Lab, University of Leeds, advised by Prof. [Mehmet Dogar](https://eps.leeds.ac.uk/computing/staff/743/professor-mehmet-dogar) and Prof. [Anthony Cohn](https://eps.leeds.ac.uk/computing/staff/76/professor-anthony-tony-g-cohn-freng-flsw-ceng-citp). 

My research focuses on the principles governing dexterous movement and control in robots and humans, particularly in continuous interactions​​. This encompasses ​​key topics including​ multi-modal perception, high-dimensional motion planning, stochastic optimal control, dynamics model learning, and their applications in​​ robotic grasping, dexterous manipulation, multi-contact legged locomotion, and compliant human-robot collaboration.
My goal is to develop robots with robust physical intelligence and dexterity, allowing them to ​​dependably perform​​ complex real-world tasks in unstructured environments—​​both autonomously and in collaboration with humans.​

<!-- / 或者更强的科研愿景： 
I envision a future where robots ​​possess​​ robust dexterity and physical intelligence, ​​allowing them to seamlessly deploy​​ alongside humans in unstructured environments and ​​dependably perform​​ complex, physically interactive tasks. -->

<!-- My goal is to enable robots to seamlessly interact with humans in crowded, chaotic environments and accomplish complex tasks. -->

**Join us:** We are looking for talented PhD/master students, research assistants, interns, postdocs, engineers, and collaborators who have a strong interest and passion in robotics and embodied intelligence ([more details]()). If you are interested in working with us, please feel free to drop me an email.

## Research Interests

My research focuses at the intersection of embodied intelligence and robotics, particularly the following areas:

- **Robot Perception:** pose estimation and tracking, tactile sensing
- **Grasp and Manipulation:** grasping, dexterous manipulation, non-prehensile manipulaiton, deformable manipulation, etc.
- **Locomotion:** dynamics and model-based control, legged locomotion, loco-manipulation, etc.
- **Human-Centered Robots:** human modeling, human-robot interaction/collaboration.  

News
======

- **[Feb. 2020]** Our paper about incremental learning is accepted to CVPR 2020.
- **[Feb. 2020]** We will host the ACM Multimedia Asia 2020 conference in Singapore!


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
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

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
