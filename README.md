# Hugo Website

Hello, and welcome to my repository for my professional website built with Hugo and hosted on github pages.

You can see the website [here](https://deloslopez.github.io/hugowebsite/)

This [Youtube video](https://www.youtube.com/watch?v=mEZ1Hj5yQ-8) was incredibly helpful in making this website and I would encourage you all to watch if you are wondering how to make your own

This [page](https://gohugo.io/hosting-and-deployment/hosting-on-github/) from hugo on how to host on Github Pages was also incredibly useful

Here is a breakdown of the most important files/folders in this repository
- content: contains the markdown files that Hugo uses to make html needed for the website
- public: Hugo uses this to create the html code needed that actually goes on the website
- static: folder for images and other files that may be used in the website
- themes: custom theme from hugo, this website's theme is ananke
- README: what you are reading right now, walks you throught the repository
- config.toml: base configuration file that outlines key characteristics of the website
- go.mod and go.sum: go files needed as Hugo is written in Go

Since this was built with Hugo, Github Actions was used as the source for build and deployment and runs a custom Hugo workflow each time there is a new push to the repository.