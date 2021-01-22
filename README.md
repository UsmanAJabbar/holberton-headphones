# HTML/CSS - Holberton Headphones
This project is a part of the Holberton School Specialization Curriculum.

On this project, we were offered a concept design file created in Figma where we were required to replicate a mockup design in HTML and CSS exclusively. The Figma mockup sketch could be found in the footer of this README.

## Overview / Notes:
- The mandatory section of the curriculum is broken down into five seperate sections, progessively adding a new section with each iteration of the index.html file.
    - Hero container Section
	    - Refer to 0-index.html.
	- Work Section
	    - Refer to 1-index.html.
	- Results Section
	    - Refer to 2-index.html.
    - Contact Us Section
	    - Refer to 3-index.html.
	- Footer Section
	    - Refer to 4-index.html.
- The project has all of its html files located in the root of the repository. Meanwhile, the required dependencies such as CSS stylesheets as well as fonts are located in the /styles, /images and /fonts directories.
- The overall structure is being handled by three seperate classes defined in the CSS file, called .section, .container, as well as .content. Furthermore, a number of native HTML tags were stylized to ensure consistency between all of the sections.
```
/* Highlight Code */
.section {
	min-height: var(--min-height-section);
	background-position: center;
	background-size: cover;
	display: flex;
	justify-content: center;
	text-align: center;
}
.container {
	/* Applies to all containers except header-container */
	max-width: var(--max-width-container);
	display: flex;
	flex-direction: column;
	padding: 6rem 1rem; 
}
.content {
	max-width: var(--max-width-content);
	display: flex;
	flex-direction: column;
	align-self: center;
}
```
- To aid further development, a number of variables were also used allowing the website to be colorized over time and updated overtime. Variables that control the accent colors of the website, as well as the height and widths of each and class mentioned above.
- By the end of the project all of the navbar menu links scroll to their respective sections.
- To ensure a touch of finesse, ensured smooth scrool's present on all of the files.

## Map
```
holberton-headphones/.
│   0-index.html
│   1-index.html
│   2-index.html
│   3-index.html
│   4-index.html
│   Holberton-School-Headphones-Figma-Concept.fig
│   README.md
│
├───images
│       favicon.ico
│       favicon.png
│       headphones_hero_1.jpg
│       headphones_hero_2.jpg
│       logo_headphones.png
│       pentagone.png
│
└───styles
    │   0-styles.css
    │   1-styles.css
    │   2-styles.css
    │   3-styles.css
    │   4-styles.css
    │   normalize.css
    │
    └───fonts
            holberton_school-icon.eot
            holberton_school-icon.svg
            holberton_school-icon.ttf
            holberton_school-icon.woff
            SourceSansPro-Black.woff2
            SourceSansPro-BlackIt.woff2
            SourceSansPro-Bold.woff2
            SourceSansPro-BoldIt.woff2
            SourceSansPro-ExtraLight.woff2
            SourceSansPro-ExtraLightIt.woff2
            SourceSansPro-It.woff2
            SourceSansPro-Light.woff2
            SourceSansPro-LightIt.woff2
            SourceSansPro-Regular.woff2
            SourceSansPro-Semibold.woff2
            SourceSansPro-SemiboldIt.woff2
            SpinCycle3DOT.woff2
            SpinCycleOT.woff2
            stylesheet.css
```

## Author
- Usman Abdul Jabbar Shaikh (hi[at]usmanjabbar.com | usmanjabbar.com)