# math_685
Stuff for pilot course


Student repos: 
@Megan-E-Luke
@planetirf
@kjohnson156


# Steps to build a simple rmarkdown website

## Option 1: start from scratch.
Read 10.5 in https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html

Minimum rq.
_site.yml
index.rmd
about.rmd

## Option 2: Find an exising site, copy, and deconstruct/reconstruct/modify
rmarkdown based website and go to it's github page. 
https://github.com/norcalbiostat/MATH130

2. FOrk the repo into your github account
3. go to settings - scroll down to "git hub pages"
    - change source --> Master branch
    - right click on the URL where it says' your site is ready to be published" and copy link
    -change repo name if you want
    - go back to code - click "Edit" under "manage topics at the top", and paste YOUR url now
    
  
  4. Clone your new fancy WORKING website repo to your computer. 
  
  ##
  STRUCTURE:
 Every RMD or MD file in your main folder will be rendered/compiled when you `Build_Website`
 Under Build --> more --> clean al will remove all rendered HTML files. 
 
  
  ## Important Files. 
  
  `.nojekyl` Necessary for when you use github to host your website. Jekyll is another "creating website engine" like Hugo (R4DS Ch10). Using this method, we will be rendering (preparing) our HTML files ourselves. WE don't want Github to do it AGAIN. WE just want GH to post our files. 
 
 files with a `_` in front, will not be rendered when you "BUILD SITE"
  
  `_site.yml`
