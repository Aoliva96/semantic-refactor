# Project Description

A study in refactoring HTML semantics

## Contents

- [Introduction](#introduction)
- [Problem](#problem)
- [Solution](#solution)
- [Deployment](#deployment)
- [Collaborators](#collaborators)
- [Resources](#resources)
- [License](#License)

## Introduction

Client desired a refactor of this projects HTML and CSS, in order to adhere to accessibility standards and enhance their site's search engine optimization. I set out to use what I've learned so far in the UC Berkeley Coding Bootcamp to refactor this project's code to improve its semantics and accessibility.

## Problem

I was given the code for this project in the following state:

- Content of the site was made up of generic divs with associated css id's and classes which harms the site's SEO.
- CSS used multiple redundant id's to apply identical attributes to HTML elements.
- HTML was not semantically legible to industry standard.
- Images lacked alt text for screen reader accessibility.

## Solution

I rectified the above problems in the following way:

- Changed generic divs of main containers to semantically appropriate HTML tags, and replaced content divs with properly identified section tags to improve SEO.
- Removed redundant CSS selectors by consolidating identical id's into classes.
- Reorganized and commented CSS to aid code legibility.
- Maintained usability of site links with unique id's not targeted by CSS (This may have a more elegant solution that I am yet unaware of).
- Added alt text to images to improve site accessibility. 
- Maintained site usage and appearance with no changes visible to the user. 

See below for a screenshot of the project post-refactor.

![Screenshot of deployed project](assets/images/semantic-refactor_screenshot.png)

## Deployment

[Link to the GitHub repo for this project](https://github.com/Aoliva96/semantic-refactor)

[Link to the deployed project on GitPages](https://aoliva96.github.io/semantic-refactor/)


## Collaborators

I collaborated with Keegan Royal-Eisenberg, George Shultz, and Joshua Jacob in a study-group on 12/12/2023, in which we compared and suggested code snippets and semantic best practices. 
I utilized suggestions made by Keegan R.E. to make the following changes to my HTML:
- Change my sidebar < section > to an < aside > tag.
- Assign a role of "navigation" to my nav tag.
- Assign a title to my "background-img" section to enhance site accessibility. 
- Suggestions for a high-quality README file, provided link to professional README resource.

I also shared the following code snippit with the other members of the 12/12/2023 study group:
- "pointer-events: none;" added to "background-img" id in CSS.
- This solves the issue of unintentional rollover text being displayed to the user, due to the "background-img" section having a "title" attribute.

## Resources

See the links below to see some of the resources I used for this project:

[Coding Bootcamp Professional README Guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)

[FreeCodeCamp HTML Anchor Tag Guide](https://www.freecodecamp.org/news/the-html-a-tag-anchor-tag-example-code/)

[SeekBrevity Semantic HTML Guide](https://seekbrevity.com/semantic-markup-important-web-design/#:~:text=Semantic%20markup%20is%20a%20way,content%20rather%20than%20its%20appearance.&text=Writing%20semantic%20markup%20means%20understanding,and%20machines%20will%20read%20it)

[Quora Post For Removing Rollover Text](https://www.quora.com/How-do-you-remove-the-hover-effect-on-an-image-using-CSS)

[W3C WAI-ARIA Accesibility Guidelines](https://www.w3.org/WAI/standards-guidelines/aria/)

## License

This project utilizes the standard MIT License.