![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 04: HTML Templating w/HandlebarsJS
===
## Code Wars Challenge

Complete [today's Kata](https://www.codewars.com/kata/simple-validation-of-a-username-with-regex) and follow the submission instructions from Lab 01.

## Lab 04 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[Handlebars Docs](http://handlebarsjs.com/)

[Arrow Functions MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

## Configuration
_Your repository must include:_

```
04-templating
└──driver-navigator
  ├── .eslintrc.json
  ├── .gitignore
  ├── LICENSE
  ├── README.md
  ├── index.html
  ├── scripts
  │   ├── article.js
  │   ├── articleView.js
  │   └── blogArticles.js
  ├── styles
  │   ├── base.css
  │   ├── layout.css
  │   └── modules.css
  └── vendor
      └── styles
          ├── fonts
          │   ├── icomoon.eot
          │   ├── icomoon.svg
          │   ├── icomoon.ttf
          │   └── icomoon.woff
          ├── icons.css
          └── normalize.css
```

## User Stories and Feature Tasks

*As a user, I want my app to render articles with consistent formatting so that I can visit the site often and have the same experience each time.*

- Include the Handlebars.js CDN in your project to replace the `$.clone()` template.

*As a developer, I want to utilize the Handlebars library to dynamically render the articles using a template so that I can easily edit the way articles are rendered.*

- Convert your existing HTML template into a Handlebars template.
- Update the `Article.prototype.toHtml()` method to utilize the Handlebars template.

*As a developer, I want to utilize modern JavaScript features so that my code is up to date with industry standards.*

- Refactor the functions and methods in your code to use ES6 arrow functions when possible.

### Stretch Goal
*As a developer, I want to use Handlebars to build my filters so that my code is more DRY.*

- Look at all that duplicated markup inside your `#filter` list items! Looks like a good opportunity to use a template. Make a small template for each filter, and re-render the list once you have data to populate it.

## Documentation
_Your README.md must include:_

```md
# Project Name

**Author**: Your Name Goes Here
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
Templating - The Goal is to use templates or create reusable templates. Subtasks in the goal were making sure the user defined input (selecting author/category) actually worked/filtered correctly and rendered

## Getting Started
1. Add script tags to hold handlebar template data - make sure data tags were relevant
2. Make sure placeholder keys, matched script tag names
3. Create and link a "working" handlebars script 
4. Refactor all of the filters to make the code drier


## Architecture
1. Using cdn version of handlebars.js (4.0)
2. Using minimized version of Jquery 3.1.1

## Change Log
Author: Eric Cobb <eric.cobb2017@gmail.com>
Date:   Sat Dec 9 13:47:42 2017 -0800
First commit - added template keys, scripts links at bottom of HTML, added template to html and script tag

Author: orsadude2 <dtcomer@gmail.com>
Date:   Sat Dec 9 13:57:28 2017 -0800
Working on ReadMe

Author: orsadude2 <dtcomer@gmail.com>
Date:   Sat Dec 9 15:53:49 2017 -0800
Refactored methods to arrows - Blog page displaying...author selector not working


## Credits and Collaborations
LINKS: https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js
LINKS: https://cdnjs.cloudflare.com/ajax/libs/handlebars.js/4.0.11/handlebars.js

Credit: The TA's for getting us unstuck on key concepts and GIT HUB; Nick for getting Eric's laptop back working (lost wifi capability) using LINUX; Amber for pointing out the small syntax errors that would keep us stuck for hours!!!!!
