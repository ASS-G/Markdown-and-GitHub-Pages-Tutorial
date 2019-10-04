<h1 align="center">
  <br>
  Markdown and GitHub Pages Tutorial
  <br>
</h1>

<p align="center">
  Sourced by Active Specialized Support Group (ASS-G)
</p>


## Index
  1. [**What is Markdown?**](#what-is-markdown)
  2. [**Intro to GitHub Pages**](#intro-to-github-pages)
  3. [**Creating a project wesite with GitHub Pages using HTML/CSS/JS**](#creating-a-project-wesite-with-github-pages-using-html-css-js)
  4. [**Creating a project wesite with GitHub Pages using Markdown**](#creating-a-project-wesite-with-github-pages-using-markdown)
  5. [**Structuring your site**](#structuring-your-site)
  6. [**Jekyll Themes**](#jekyll-themes)

## What is Markdown?
Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`.

You can use Markdown most places around GitHub


## Intro to GitHub Pages

Creating websites for your projects is easy with GitHub Pages. This site is an example - a simple GitHub Pages website, hosted through github.io, written primarily in HTML/CSS, also provided by GitHub. The video offers a [quick introduction to this service]("https://www.youtube.com/embed/2MsN8gpT6jY")

## Creating a project wesite with GitHub Pages using HTML/CSS/JS
To create a GitHub pages site for a particular project from HTML files, you:
1. Log in to your GitHub account and create a new repository, or go to an existing one
2. Upload your webpage files (HTML,CSS,js) to the project repository via Git. Make sure index.Html is present as that is considered as the starting page of the project website
3. Click on the Settings tab on the upper right of the project page
4. Scroll down to the GitHub pages section. Press choose a theme to select a Jekyll theme, or simply select the master branch as the source.


## Creating a project wesite with GitHub Pages using Markdown
To create a GitHub pages site for a particular project, you:
1. Log in to your GitHub account and create a new repository, or go to an existing one
2. Click on the Settings tab on the upper right of the project page
3. Scroll down to the GitHub pages section. Press choose a theme to select a Jekyll theme, or simply select the master branch as the source if you'd like to build your site from scratch
4. Now you can use the online editor to add to maintain and preview the content for your website in markdown files, or make changes locally and push them to your project repo via git

**Note: Just remember to commit your changes when you're done!**

Whenever I commit to this repository, whether on my local machine or by editing files directly on GitHub, GitHub Pages will automatically rebuild the pages in the site, from the content in the associated HTML/CSS/JS files.


## Structuring your site

**index.html, is the index for this site.**
But it doesn't need to be the only page. You can create new pages for your site in GitHub or locally with git, and then add them to your index to build a more complete website. (Note that I could also have used markdown for this site, if I had named this page **README.md** without index.html)

For example, [here's a link to another page in this repo](/markdown.md), which includes additional resources for learning Markdown.

## Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your repository settings. The name of this theme is saved in the Jekyll `_config.yml` configuration file.

You can learn more about Jekyll websites [here](https://jekyllrb.com/).

To learn more about structuring your site with custom templates, [see this great guide by Jonathan McGlone](http://jmcglone.com/guides/github-pages/)


## Support or Contact

Having trouble with Pages? Check out more [documentation](https://help.github.com/categories/github-pages-basics/).


###### [[Back to Top]](#----github-pages-tutorial--)

![wave](http://cdn.thekrishna.in/img/common/border.png)
