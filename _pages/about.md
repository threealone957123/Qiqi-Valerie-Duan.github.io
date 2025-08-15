---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Qiqi Duan, a passionate and dedicated M.Phil. student in Data Science and Analytics at [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/zh/?variant=zh-cn/). With a strong academic background and diverse research experience, I am committed to exploring the intersection of data science, machine learning, and real-world applications. My journey in academia and industry has equipped me with a unique skill set and a drive to tackle complex problems through innovative solutions.


Education
======
**The Hong Kong University of Science and Technology (Guangzhou)**
• M.Phil. in Data Science and Analytics (Aug. 2022 - Oct. 2023)
• GPA: 3.76/4
• Academic papers: 3
• Co-author of multiple research papers published in top-tier conferences like NeurIPS
**The Chinese University of Hong Kong (CUHK)**
• M.Sc. in Systems Engineering and Engineering Management
**Nankai University**
• B.Mgmt. in International Accounting (Sep. 2012 - July 2016)
• GPA: 87.6/100, ranking top 15%
• Recipient of the Academic Year Scholarship
• Recipient of annual full-fund exchange opportunity to University of Pompeu Fabra (Barcelona, Spain)

Publications
======
1. Goldman: Reading the Fed, Riding the Trend in Gold Markets with Multi-Agent LLMs
  • Authors : Qiqi Duan, Changlun Li, Yao Shi, Yizhang Zhu, Yuyu Luo, Nan Tang
  • Conference : NeurIPS 2025 (Under Review)
  • Abstract : This paper presents a multi-agent system that leverages large language models (LLMs) to optimize decision-making in the gold market by            incorporating real-time geopolitical, inflation, and policy data.
2. Time Travel is Cheating: Going Live with DeepFund for Real-Time Fund Investment Benchmarking
  • Authors : Changlun Li, Yao Shi, Chen Wang, Qiqi Duan, Runke Ruan, Weijie Huang, Haonan Long, Lijun Huang, Yuyu Luo, Nan Tang
  • Conference : NeurIPS 2025 (Under Review)
  • Abstract : This research addresses potential information leakage in LLM-driven trading strategies by evaluating them in real-time testing environments.      It also includes contributions to agent functionality development and experimental validation.
3. Automatic Modeling and Analysis of Students' Problem-Solving Handwriting Trajectories
  • Authors : Zhonghua Sheng, Shuyu Shen, Leixian Shen, Qiqi Duan, Nan Tang, Pan Hui, Huamin Qu, Yuyu Luo
  • Conference : AIED
  • Abstract : This study focuses on modeling handwriting trajectories to reveal students' problem-solving behaviors. It contributes to the development of       educational tools that enhance learning analytics.

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
