# Simple Resume Website

A single-page, responsive online resume. Built for Task 3 (Simple Resume Website) of my Web Development internship.

**Live page:** https://cedrick40.github.io/resume-website/

## About the project

The page presents my resume online: my profile, experience, education, projects, skills, and contact information. It is built from my CV, reorganized into a clean layout that is easy to scan.

## Objective

To practice organizing structured information with semantic HTML and styling it with CSS.

## Tools used

- HTML5
- CSS3
- VS Code
- Git and GitHub (free)

## Sections

- **Profile:** a short summary
- **Experience:** my web development internship
- **Education:** my degree and university
- **Projects:** a multi-tenant lodge management system and an academic team project
- **Skills:** grouped into languages and frameworks, concepts, tools, and professional skills
- **Contact:** location, phone, email, GitHub, LinkedIn, and availability

## My approach

1. **Planning:** I took the content from my CV and sorted it into the six sections the task requires, rewriting it to be short and clear.
2. **Semantic HTML:** I used `aside` for the sidebar, `main` for the main content, `section` for each part of the resume, and `article` for each experience, education, and project entry. Contact details are inside an `address` element, dates use the `time` element, and the headings follow a clear order (`h1` for my name, `h2` for sections, `h3` for entries).
3. **Lists:** Skills and the details of each entry are written as lists, so they are easy to scan.
4. **CSS Grid for the page layout:** `grid-template-columns: 300px 1fr` creates a fixed sidebar on the left and a flexible main column on the right.
5. **Flexbox for small parts:** each entry's heading row uses `display: flex` with `justify-content: space-between`, so the title is on the left and the date is on the right.
6. **Readability:** a clear size hierarchy, comfortable line height, a blue and white palette, muted gray for dates, thin dividing lines, and consistent spacing.
7. **Responsive layout:** a media query at 760px turns the grid into a single column, reduces padding, and stacks each title above its date. `overflow-wrap: anywhere` keeps long links, such as the email address, inside the sidebar.
8. **Testing:** I checked the page at desktop size and in the browser's phone view.

## Project structure

```
resume-website/
├── index.html
├── style.css
└── README.md
```

## Outcome

A clean, professional, and responsive resume page that includes all the required sections and works on desktop and mobile. This task taught me how semantic tags give structure to content, when to use Grid and when to use Flexbox, and how spacing, hierarchy, and color make a page easier to read.

## Author

Cedrick Niyibikora

- GitHub: https://github.com/Cedrick40
- LinkedIn: https://www.linkedin.com/in/cedrick10
