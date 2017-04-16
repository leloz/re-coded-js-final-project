# Re:Coded Final Project Review Checklist

**Name of project developer**: Saber Rasheed

**Link to project's GitHub repository**: Saber20.github.io


## Function
### AJAX Requests
- [x] All AJAX requests work properly.
- [yes] Large images, videos, and other media — anything that would significantly slow down the user's browsing experience — are loaded via AJAX requests.

### JavaScript Style
- [yes] Each page has its own JavaScript file that contains JavaScript written specifically for that page.
- [yes every function it has it's work] All functions have exactly **ONE** responsibility. No functions do more than one thing, like make an AJAX request *and* add the returned data to the DOM.
+ **List any functions that have more than a single responsibility**: 

## Form
### Pages
#### Homepage
- [yes] Project has a homepage.
- [yes] Homepage loads well-styled content even when JavaScript is disabled.
- [yes] Homepage contains links to all other pages.
- [No, the paragraph it's not clear and he repeated the sentences for two times] Homepage makes the website's purpose clear (who owns the site / what we can expect to find within).

#### About
- [yes] Project has an About page.
- [yes, he talk about his life before Re:Coded, but he used the abbreviation, if he didn;t use it it will be better] Contains one paragraph about the student's life before Re:Coded.
- [yes ] Contains one paragraph about why the student joined Re:Coded.
- [yes, but he didn;t write about his dreams ] Contains one paragraph about what the student wants to do after Re:Coded, both short- and long-term.

#### Projects
- [yes ] Project has a Projects page.
- [yes ] Projects page contains two navigational buttons or tabs, `Current` and `Favorite`.
- [yes ] Clicking the `Current` button makes an AJAX request to the GitHub API and displays information about the student's 5 most recent GitHub repositories.
- [yes ] Clicking the `Favorite` button makes an AJAX request and displays a list of GitHub repositories (that the student created or contributed to) that the student is especially proud of.

#### Skills
- [yes ] Project has a Skills page.
- [in his code he write it but on the page I did not see it ] Skills page displays information about all of the student's programming skills.
- [yes ] Information about student's skills is stored in a JSON file in the project directory.
+ **Name of file**: 
- [yes ] Skills are added to the page by loading the JSON file via an AJAX request.

#### Student's Choice
- [yes ] Project contains at least one more page that displays data from an API *other than GitHub*.
+ **Which API**: 
- [yes ] Page loads data via an AJAX call to the appropriate API.

## Style
### Overall
- [yes ] Website looks professional.
+ **Why? Describe it**: The website looks professional and it's simple, it's clear instead of homepage, the color it's suitable and the design it's nice
- [No it does not feel cluttered ] Website does not feel cluttered.
- [ ] Spacing between similar elements is consistent across all pages. (For example, the amount of space between the navbar and the page's content is identical on every page.)
- [yes it's similar ] Sizing of similar elements is consistent across all pages. (For example, the navbar links on each page are identical.)
- [yes it's readable ] All text is readable. For example, there isn't black text on top of a dark image or green text on a red background.
- [yes the same color ] Website has a uniform color scheme. Aside from images, the same base colors are used on every page of the site.
- [yes ] Website has a uniform style / layout. It should feel like one cohesive site and not just a random collection of pages thrown together.

### Code
- [yes ] JavaScript functions and variables have descriptive names.
+ Good: `var favoriteProjects = ...`
+ Bad: `function a (b, c, d) { ... }`
- [yes the spell it's correct ] JavaScript functions and variables that are composed of English words are spelled correctly.
+ Good: `function sendRequestToGitHub (address, data, token) { ... }`
+ Bad: `function sndreqestGithub (adres, data, tokin) { ... }`
- [ not in every where the name it's clear ] HTML elements and attributes (for example, IDs and classes) have descriptive names.
+ Good: `<project id="favoriteProject1" class="projects favoriteProjects">`
+ Bad: `<pj id="p1" class="ps fps">`
- [yes ] HTML elements and attributes that are composed of English words are spelled correctly.
+ Good: `<project id="favoriteProject1" class="projects favoriteProjects">`
+ Bad: `<projet id="favritProjet1" class="projets favritProjets">`

### Content
- [In navebar(project it should be projects) ] There are no spelling or grammar errors in the site's textual content (including headings, navigational links, and other small elements).

### Pages
#### Student's Choice
- [yes ] Student used one of the examples given in the [final project guidelines](https://github.com/gj/re-coded-js-final-project/blob/master/README.md).
+ **List example**: 
- [yes ] Student came up with their own, creative idea.
+ **List idea**: 

## Linters
- [ I did not noticed mistakes in JavaScript] I ran the student's JavaScript code through [JSLint](http://jslint.com/) and told them about any JavaScript issues.


- [(here the link for index file mistake) https://validator.w3.org/nu/?doc=https%3A%2F%2Fgithub.com%2FSaber20%2FSaber20.github.io%2Fblob%2Fmaster%2Findex.html &&

(Youtube file: https://validator.w3.org/nu/?doc=https%3A%2F%2Fgithub.com%2FSaber20%2FSaber20.github.io%2Fblob%2Fmaster%2FPages%2Fyoutube.html)&&

(work file: https://validator.w3.org/nu/?doc=https%3A%2F%2Fgithub.com%2FSaber20%2FSaber20.github.io%2Fblob%2Fmaster%2FPages%2Fworkex.html)&&


(skills file: https://validator.w3.org/nu/?doc=https%3A%2F%2Fgithub.com%2FSaber20%2FSaber20.github.io%2Fblob%2Fmaster%2FPages%2Fskills.html)&&

(about file: https://validator.w3.org/nu/?doc=https%3A%2F%2Fgithub.com%2FSaber20%2FSaber20.github.io%2Fblob%2Fmaster%2FPages%2Fabout.html)&&

(projects file: https://validator.w3.org/nu/?doc=https%3A%2F%2Fgithub.com%2FSaber20%2FSaber20.github.io%2Fblob%2Fmaster%2FPages%2Fprojects.html)

OPEN THIS LINKS AND YOU WILL FIND YOU MISTAKES!





] I ran the student's HTML code through [the W3C's HTML validator](https://validator.w3.org/nu/) and told them about any HTML issues.

- [(about file: you have a parsing error in line 3, 9),
(home file: you have a parsing error in line 27, 127),
(project file: you have a parsing error in line 2, 12),
(skills file: you have a parsing error in line 2),
((work file: you have a parsing error in line 7),
( youtube file: you have a parsing error in line 3, 9)
] I ran the student's CSS code through [CSS Lint](http://csslint.net/) and told them about any CSS issues.

**Name of reviewer**: Leloz Sulaiman
