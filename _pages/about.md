---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<h1 style="color: #000000;"> caojiale(曹家了)</h1>
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).


A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.
<P>
<SCRIPT type=text/javascript>
<!--
// Toggle Display of BibTeX
function toggleBibtex(articleid) {
  var bib = document.getElementById(articleid);
  // Toggle
    if(bib.style.display == "none") {
      bib.style.display = "";
    }
    else {
      bib.style.display = "none";
    }
}
-->
</SCRIPT>

<SCRIPT type=text/javascript>

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-40926388-1']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</SCRIPT>
</P>
<a href="javascript:toggleBibtex('cao2021pedsurvey')"  target=_self><font color="dimgray" face="Arial" style="font-size: 11pt;">[Bibtex]</font></a>
<div id=cao2021pedsurvey class=blockcontent style="DISPLAY: none">
<pre>
@article{cao2021pedsurvey,
  title={From Handcrafted to Deep Features for Pedestrian Detection: A Survey},
  author={Jiale Cao and Yanwei Pang and Jin Xie and Fahad Shahbaz Khan and Ling Shao},
  journal={arXiv:2010.00456},
  year={2021},
}
</pre></div>
 
Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).




<a href="#" class="custom-link" onclick="toggleContent('content2'); return false;">点击展开/隐藏内容2<br></a>
<div id="content2" class="hidden-content">
   <div id="liu2023self" class="hidden-content">
  <p style="text-indent: 2em;">@article{liu2023self,<br>
      title={Self-Consistent Graph Neural Networks for Semi-Supervised Node Classification},<br>
      author={Liu, Yanbei and Zhao, Shichuan and Wang, Xiao and Geng, Lei and Xiao, Zhitao and Lin, Jerry Chun-Wei},<br>
      journal={IEEE Transactions on Big Data},<br>
      volume={9},<br>
      number={4},<br>
      pages={1186--1197},<br>
      year={2023},<br>
      publisher={IEEE}<br>
}</p>
</div>  



Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

<a href="#" class="custom-link" onclick="toggleContent('content3'); return false;">点击展开/隐藏内容3<br></a>
<div id="content3" class="hidden-content">
    这里是隐藏的内容3。
</div>  

<script>
function toggleContent(contentId) {
    var content = document.getElementById(contentId);
    if (content.style.display === 'none') {
        content.style.display = 'block';
    } else {
        content.style.display = 'none';
    }
}
</script>

</body>
</html>
