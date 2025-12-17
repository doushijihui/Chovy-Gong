---
permalink: /
title: "Chaoyu (Chovy) Gong"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am now a Research Fellow in College of Computing and Data Science (CCDS) @NTU, working with [Prof. Luo Siqiang](https://siqiangluo.com/). In Spring 2026, I will join Southeast University (SEU) as a tenure-track Associate Professor. 

I earned my Ph.D. and B.Eng. from the SEU. I was a Research Fellow at the School of Computing (SoC) @NUS, where I was affiliated with [HPC-AI-LAB](https://ai.comp.nus.edu.sg/). I also served as a Senior Research Scientist at an AI startup, focusing on the acceleration training of a powerful video generation model [Open-Sora](https://huggingface.co/hpcai-tech/Open-Sora-v2).  My research lies at the intersection of **scalable machine learning**, **uncertainty-aware modeling**, and **efficient training of large models**. For more details, please see my CV.

In addition to academic research, I also design and implement high-frequency trading (HFT) strategies, focusing on algorithmic execution and multi-market arbitrage. 

Education 
======

**Ph.D.** (Recommended for Conferment)  
Southeast University (SEU), Nanjing, China  
*Sep. 2016 – Jun. 2022*  
- Major: Energy and Information Engineering & Automation  
- Advisors: Prof. Pei-hong Wang and Prof. [Zhi-gang Su](https://power.seu.edu.cn/szg/list.htm)  

**Visiting Scholar**  
School of Computing, National University of Singapore (NUS), Singapore  
*Apr. 2021 – Apr. 2022*  
- Advisor: Prof. [Yang You](https://www.comp.nus.edu.sg/~youy/)

**B.Eng. in Engineering**  
School of Energy and Environment, Southeast University (SEU), Nanjing, China  
*Aug. 2012 – Jun. 2016*


Selected Pubications 
======
<sup>†</sup> Equal contribution, <sup>✉</sup> Corresponding Author， More Paper in [google scholar](https://scholar.google.com.sg/citations?user=sp6xe90AAAAJ&hl=zh-CN) 

Haoyu Liu <sup>†</sup>, **Chaoyu Gong** <sup>†</sup>, et.al  
*When Deepfake Detection Meets Graph Neural Network: a Unified and Lightweight Learning Framework*  
**KDD**, 2026.

Yong Liu, Zirui Zhu, **Chaoyu Gong**<sup>✉</sup>, et.al  
*Sparse mezo: Less parameters for better performance in zeroth-order llm fine-tuning*  
**Neurips**, 2025.

Yunshu Shi, **Chaoyu Gong**<sup>✉</sup>, et.al  
*Time-Series Clustering With Dynamic Feature Mining in the Framework of Belief Function Theory*  
**IEEE TSMC**, 2025.

**Chaoyu Gong**, et.al  
*Multi-view Evidential K-NN Classification*  
**Information Fusion**, 2025.

**Chaoyu Gong**, et.al  
*Distributed and Joint Evidential K -Nearest Neighbor Classification*  
**IEEE TKDE**, 2024.

**Chaoyu Gong**, et.al  
*Scalable Evidential K -Nearest Neighbor Classification on Big Data*  
**IEEE TBD**, 2024.

**Chaoyu Gong**, et.al  
*Sparse Reconstructive Evidential Clustering for Multi-view Data*  
**IEEE/CAA Journal of Automatica Sinica**, 2023.

**Chaoyu Gong**, et.al  
*Joint Evidential K-Nearest Neighbor Classification*  
**IEEE ICDE**, 2022.

**Chaoyu Gong**, et.al  
*Self-reconstructive evidential clustering for high-dimensional data*  
**IEEE ICDE**, 2022.

**Chaoyu Gong**, et.al  
*A Sparse Reconstructive Evidential K-Nearest Neighbor Classifier for High-dimensional Data*  
**IEEE TKDE**, 2022.

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
