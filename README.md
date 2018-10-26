## DANGER !!! THIS IN AN UNMAINTAINED FORK !!!

[The true jekyll-algolia is here.](https://github.com/algolia/jekyll-algolia)

This fork integrates :
 - [Avoiding autopages from jekyll paginate v2 to be indexed #91](https://github.com/algolia/jekyll-algolia/pull/91)
 - [Raise custom exception instead of SystemExit #85](https://github.com/algolia/jekyll-algolia/pull/85)
 
 And I use it on Netlify by configuring my Gemfile like this :
 
     gem 'jekyll-algolia', :git => "https://github.com/djacquel/jekyll-algolia.git", :branch => 'develop'
 
 
