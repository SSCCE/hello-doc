[![Build Status](https://img.shields.io/travis/SSCCE/hello-doc/master.svg?label=Build)](https://travis-ci.org/SSCCE/hello-doc)
## hello-doc ##

Illustrates an [issue of gradle-git-publish](https://github.com/ajoberstar/gradle-git-publish/issues/51) 1.0.0.

Travis CI is configured to execute the following gradle tasks: 
 - `genDoc` - generates a simple HTML document
 - `gitPublishPush` - publishes the HTML document to gh-pages

The published document should be available [here](https://SSCCE.github.io/hello-doc).
