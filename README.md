<h1 align="center">
  <br>
  GitHub Pages Tutorial
  <br>
</h1>

<p align="center">
  Sourced by Active Specialized Support Group (ASS-G)
</p>

## Intro to GitHub Pages

Creating websites for your projects is easy with GitHub Pages. This site is an example - a simple GitHub Pages website, hosted through github.io, written primarily in HTML/CSS, also provided by GitHub. The video offers a [quick introduction to this service]("https://www.youtube.com/embed/2MsN8gpT6jY")

### Creating a project wesite with GitHub Pages using Markdown
To create a GitHub pages site for a particular project, you:
1. login to your GitHub account and create a new repository, or go to an existing one
2. click on the Settings tab on the upper right of the project page
3. scroll down to the GitHub Pages section. Press Choose a theme to select a Jekyll theme, or simply select the Master branch as the source if you'd like to build your site from scratch
4. Now you can use the online editor to add to maintain and preview the content for your website in Markdown files, or make changes locally and push them to your project repo via git

##### JUST REMEMBER TO COMMIT YOUR CHANGES WHEN YOU'RE DONE!

Whenever I commit to this repository, whether on my local machine or by editing files directly on GitHub, GitHub Pages will automatically rebuild the pages in the site, from the content in the associated HTML/CSS/JS files.

-----------

## Structuring your site

##### index.html, is the index for this site.
But it doesn't need to be the only page. You can create new pages for your site in GitHub or locally with git, and then add them to your index to build a more complete website. (Note that I could also have used markdown for this site, if I had named this page **README.md**.)

For example, [here's a link to another page in this repo](/markdown.md), which includes additional resources for learning Markdown.

#### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your repository settings. The name of this theme is saved in the Jekyll `_config.yml` configuration file.

You can learn more about Jekyll websites [here](https://jekyllrb.com/).

To learn more about structuring your site with custom templates, [see this great guide by Jonathan McGlone](http://jmcglone.com/guides/github-pages/)

------------

## Additional Documentation

- Find more info about [GitHub Pages here](https://pages.github.com/)
- For instructions on how to create a copy of this repo in your own GitHub account and (optionally) to use git to manage your project files, [see this walkthrough](/walkthrough.md)
- For more information about version control with git, [see this quick introduction](/git.md)
- For help incorporating mathematical notations using MathJax in your site, [see this page](/mathjax.md)

------------

## Support or Contact

Having trouble with Pages? Check out more [documentation](https://help.github.com/categories/github-pages-basics/).


###### [[Back to Top]](#----github-pages-tutorial--)

![wave](http://cdn.thekrishna.in/img/common/border.png)
