---
# Notes:  Jekyl tinkering:
layout: default
---
Notes:  random jekyll stuff

bundle exec jekyll serve

or good for testing:

bundle exec jekyll serve --livereload
- should refresh.  

![testimagesyntaxinmarkdn](images/muhabura.jpg)  


```
jekyll build - Builds the site and outputs a static site to a directory called _site.
jekyll serve - Does jekyll build and runs it on a local web server at http://localhost:4000, rebuilding the site any time you make a change. 
```
assets should be this easy, run simple tests confirm:

```
Using CSS, JS, images and other assets is straightforward with Jekyll. Place them in your site folder and they’ll copy across to the built site.

Jekyll sites often use this structure to keep assets organized:

.
├── assets
│   ├── css
│   ├── images
│   └── js
...
So, from your assets folder, create folders called css, images and js. Additionally, directly under the root create another folder called ‘_sass’, which you will need shortly.
```


