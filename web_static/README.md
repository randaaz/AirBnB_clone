# AirBnB Clone - Web Static

This project focuses on building the front end of the AirBnB Clone step by step, starting with designing, prototyping, and implementing HTML and CSS elements.

## Project Details

- **By:** Guillaume
- **Weight:** 1
- **Project Start:** Jan 18, 2024, 6:00 AM
- **Project End:** Jan 23, 2024, 6:00 AM
- **Manual QA Review:** Must be done (request it when you are done with the project)

## Concepts

For this project, the following concepts are expected to be explored:

- HTML/CSS
- The trinity of front-end quality

## Background Context

The project involves creating simple HTML static pages, a style guide, and fake contents. No Javascript or data loaded from external sources is allowed during this phase.

Before starting, please fork or clone the repository "AirBnB_clone" from your partner if you were not the owner of the previous project.

## Resources

Read or watch:

- Learn to Code HTML & CSS (until “Creating Lists” included)
- Inline Styles in HTML
- Specifics on CSS Specificity
- CSS SpeciFishity
- Introduction to HTML
- CSS MDN
- Center boxes

## Learning Objectives

By the end of this project, you are expected to be able to explain the following without the help of Google:

- What is HTML
- How to create an HTML page
- What is a markup language
- What is the DOM
- What is an element / tag
- What is an attribute
- How does the browser load a webpage
- What is CSS
- How to add style to an element
- What is a class
- What is a selector
- How to compute CSS Specificity Value
- What are Box properties in CSS

## Copyright - Plagiarism

- You are tasked to come up with solutions for the tasks yourself to meet the above learning objectives.
- You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
- You are not allowed to publish any content of this project.
- Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements

- Allowed editors: vi, vim, emacs
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should be W3C compliant and validate with W3C-Validator
- All your CSS files should be in the "styles" folder
- All your images should be in the "images" folder
- You are not allowed to use !important and id (#... in the CSS file)
- You are not allowed to use tags img, embed, and iframe
- You are not allowed to use Javascript
- Current screenshots have been done on Chrome 56 or more.
- No cross browsers
- You have to follow all requirements, but some margin/padding are missing - you should try to fit as much as you can to screenshots

## Tasks

The project involves several tasks, each building on the previous one, starting with simple HTML pages and progressively adding more complex features.

1. **Inline styling**
   - Write an HTML page that displays a header and a footer.
   - Layout: Body with no margin or padding, Header with red color, Footer with green color and text centered vertically and horizontally always at the bottom of the page.
   - Requirements: Use header and footer tags, no import of files, inline styling for all tags.

   Repo:
   - GitHub repository: [AirBnB_clone]
   - Directory: web_static
   - File: 0-index.html

2. **Head styling**
   - Write an HTML page that displays a header and a footer using the style tag in the head.
   - Requirements: Use header and footer tags, no import of files, use the style tag in the head.

   Repo:
   - GitHub repository: [AirBnB_clone]
   - Directory: web_static
   - File: 1-index.html

3. **CSS files**
   - Write an HTML page that displays a header and a footer using CSS files.
   - Requirements: Use header and footer tags, no inline styling, have 3 CSS files: `styles/2-common.css` for global style, `styles/2-header.css` for header style, `styles/2-footer.css` for footer style.

   Repo:
   - GitHub repository: [AirBnB_clone]
   - Directory: web_static
   - File: 2-index.html, styles/2-common.css, styles/2-header.css, styles/2-footer.css


4. **Search!**
   - Write an HTML page that displays a header, footer, and a filters box with a search button.
   - Layout (based on 3-index.html): Container with a div between header and footer tags, containing a section for filters, a button for search, and styling specifications.
   - Requirements: Use header, footer, section, and button tags, no inline style, have 4 CSS files: `styles/4-common.css` for global style, `styles/3-header.css` for header style, `styles/3-footer.css` for footer style, `styles/4-filters.css` for filters style.

   Repo:
   - GitHub repository: [AirBnB_clone]
   - Directory: web_static
   - File: 4-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/4-filters.css, images/

5. **More filters**
   - Write an HTML page that displays a header, footer, and a filters box with additional filters for locations and amenities.
   - Layout (based on 4-index.html): Additional divs for locations and amenities filters with titles and subtitles, and styling specifications.
   - Requirements: Use header, footer, section, h3, h4 tags, no inline style, have 4 CSS files: `styles/4-common.css` for global style, `styles/3-header.css` for header style, `styles/3-footer.css` for footer style, `styles/5-filters.css` for filters style.

   Repo:
   - GitHub repository: [AirBnB_clone]
   - Directory: web_static
   - File: 5-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/5-filters.css, images/

6. **It's (h)over**
   - Write an HTML page that displays a header, footer, a filters box with a dropdown, and additional styling for hover effects.
   - Layout (based on 5-index.html): Dropdowns displayed on mouse hover for location and amenity filters, with specific styling.
   - Requirements: Use header, footer, section, ul, li, h2 tags, no inline style, have 4 CSS files: `styles/4-common.css` for global style, `styles/3-header.css` for header style, `styles/3-footer.css` for footer style, `styles/6-filters.css` for filters style.

   Repo:
   - GitHub repository: [AirBnB_clone]
   - Directory: web_static
   - File: 6-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, images/

7. **Display results**
   - Write an HTML page that displays a header, footer, a filters box with a dropdown, and results section.
   - Layout (based on 6-index.html): Results section with a title and multiple places as listings, each described by an article.
   - Requirements: Use header, footer, section, article, h1, h2 tags, no inline style, have 5 CSS files: `styles/4-common.css` for global style, `styles/3-header.css` for header style, `styles/3-footer.css` for footer style, `styles/6-filters.css` for filters style, `styles/7-places.css` for places style.

   Repo:
   - GitHub repository: [AirBnB_clone]
   - Directory: web_static
   - File: 7-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, styles/7-places.css, images/

8. **More details**
   - Write an HTML page that displays a header, a footer, a filter box with a dropdown list, and additional details for each place.
   - Layout (based on 7-index.html): Additional details for each place, including price by night, information section, user section, and description section.
   - Requirements: Use header, footer, section, article, div, h1, h2, h3, h4, ul, li tags, no inline style, have 5 CSS files: `styles/4-common.css` for global style, `styles/3-header.css` for header style, `styles/3-footer.css` for footer style, `styles/6-filters.css` for filters style, `styles/8-places.css` for places style.

   Repo:
   - GitHub repository: [AirBnB_clone]
   - Directory: web_static
   - File: 8-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters
- *** And 4 advanced tasks *** 
