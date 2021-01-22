![Holberton-Headphones-Cover-Image UsmanJabbar.COM](https://github.com/UsmanGTA/holberton-headphones/blob/main/extras/Holberton-Headphones-Cover.jpg)
# HTML/CSS - Holberton Headphones
This project is a part of the Holberton School Specialization Curriculum.

On this project, we were offered a concept design file created in Figma where we were required to replicate a mockup design in HTML and CSS exclusively. The Figma mockup sketch could be found in the extras folder.

## Overview / Notes:
- The mandatory section of the curriculum is broken down into five seperate sections, progessively adding a new section with each iteration of the index.html file.
    - Hero Section
	- Work Section
	- Results Section
    - Contact Us Section
	- Footer Section
- The project has all of its html files located in the root of the repository. Meanwhile, the required dependencies such as CSS stylesheets as well as fonts are located in the /styles, /images and /fonts directories.
- The overall structure is being handled by three seperate classes defined in the CSS file, called .section, .container, as well as .content. Furthermore, a number of native HTML tags were stylized to ensure consistency between all of the sections.
```
/* Section/Container Variables */
:root {
	/* Content Width */
	--min-height-section: 600px;
	--max-width-container: 1000px;
	--max-width-content: 630px;
}
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

## Author
- Usman Abdul Jabbar Shaikh (hi[at]usmanjabbar.com | usmanjabbar.com)