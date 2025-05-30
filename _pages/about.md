---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently a PhD student in the [School of Computer Science & Technology](https://cs.hust.edu.cn) at the [Huazhong University of Science and Technology](https://www.hust.edu.cn), where I am supervised by [Dr. Haikun Liu](https://www.cs.ox.ac.uk/people/Mark.Harman/).
I am affiliated with the [National Engineering Research Center for Big Data Technology and System, the Services Computing Technology and System Lab and the Cluster and Grid Computing Lab](https://grid.hust.edu.cn/index.htm).

My primary research interests stream processing, transactional consistency, and
parallel recovery, with a particular focus on scalable
transactional stream processing on multicore
processors and distributed environments.

I also actively collaborate with [Dr.Shuhao Zhang](https://shuhaozhangtony.github.io/) on innovative research in the field of parallel database
systems, large language model (LLM) inference frameworks, and their
integration with stream processing techniques.

Publications
======
1. **Jianjun Zhao**, Haikun Liu, Shuhao Zhang, Yancan Mao, Zhuohui Duan, Xiaofei Liao, Hai Jin, Yu Zhang.  
   *Towards High-Performance Transactional Stateful Serverless Workflows with Affinity-Aware Leasing*.  
   In *Proceedings of the 2025 USENIX Annual Technical Conference (USENIX ATC)*, Boston, MA, USA, July 7–9, 2025. USENIX Association, 2025:1890–1910.  
   *(CCF A conference; EI indexed; Affiliation: Huazhong University of Science and Technology)*

2. **Jianjun Zhao**, Yancan Mao, Zhonghao Yang, Haikun Liu, Shuhao Zhang.  
   *Scalable Transactional Stream Processing on Multicore Processors*.  
   *IEEE Transactions on Knowledge and Data Engineering (TKDE)*, Early Access, 2025.  
   [DOI:10.1109/TKDE.2025.3556741](https://doi.org/10.1109/TKDE.2025.3556741)  
   *(CCF A journal; SCI indexed; IF: 8.9; Affiliation: Huazhong University of Science and Technology)*

3. **Jianjun Zhao**, Haikun Liu, Shuhao Zhang, Zhuohui Duan, Xiaofei Liao, Hai Jin, Yu Zhang.  
   *Fast Parallel Recovery for Transactional Stream Processing on Multicores*.  
   In *Proceedings of the 2024 IEEE 40th International Conference on Data Engineering (ICDE)*, Utrecht, Netherlands, May 13–16, 2024. IEEE, 2024:1478–1491.  
   *(CCF A conference; EI indexed; Affiliation: Huazhong University of Science and Technology)*

4. Yancan Mao, **Jianjun Zhao**, Shuhao Zhang, Haikun Liu, Volker Markl.  
   *MorphStream: Adaptive Scheduling for Scalable Transactional Stream Processing on Multicores*.  
   In *Proceedings of the 2023 International Conference on Management of Data (SIGMOD)*, Washington, USA, June 18–23, 2023. ACM, 2023:1–16.  
   *(CCF A conference; EI indexed; Co-first author; Affiliation: Huazhong University of Science and Technology)*

5. Siqi Xiang, Zhonghao Yang, **Jianjun Zhao**, Yancan Mao, Shuhao Zhang.  
   *MorphStream: Scalable Processing of Transactions over Streams*.  
   In *Proceedings of the 2024 IEEE 40th International Conference on Data Engineering (ICDE Demo)*, Utrecht, Netherlands, May 13–16, 2024. IEEE, 2024:5485–5488.  
   *(CCF A conference; EI indexed; Affiliation: Huazhong University of Science and Technology)*

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
