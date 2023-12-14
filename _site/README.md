# cv

Fork from [markdown-cv](http://elipapa.github.io/markdown-cv)

markdown-cv
markdown-cv is a simple template to list all your accomplishments in a readable Markdown file. It uses CSS to style your text into a stylish web page. It can also be printed as PDF.

Usage
Edit directly in github the `index.md` file adding your skills, jobs and education.


To transform your plain text CV into a beautiful looking HTML page and share it you then have two options:

1) USING GITHUB PAGES TO PUBLISH IT ONLINE
   Delete the existing gh-pages branch from your fork. It will only contain this webpage. You can either use git or the github web interface
   Create a new branch called gh-pages (which will then be a copy of master)
   Head to yourusername.github.io/markdown-cv to see your CV live.
   Any change you want to make to your CV from then on would have to be done on the gh-pages branch and will be immediately rendered by Github Pages.

2) BUILD IT LOCALLY
   install jekyll on your computer. `gem install jekyll` will do for most users.
   Clone your fork on your computer
   Type `jekyll serve` and you’ll be able to see your CV on your local host (the default address is http://localhost:4000).
   You can edit the `index.md` file and see changes live in your browser.
   How do I print the PDF?
   Whether you used Github Pages or a local installation of Jekyll, to print a PDF just press Print in your browser. Print specific CSS media queries will take care of the styling.

The included CSS renders your CV in different styles:
- kjhealy the original default, inspired by kjhealy’s vita template
- davewhipp is a tweaked version of kjhealy, with bigger fonts and dates right aligned, authored by David Whipp

To change the default style, one needs to simply change site the variable in the _config.yml file.


LICENSE
MIT License