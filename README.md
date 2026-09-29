# ohuru-ian.github.io

Source for my personal portfolio: **[ohuru-ian.github.io](https://ohuru-ian.github.io)**

A fast single-page site listing my skills, selected projects and experience, with a downloadable CV. It is hand-written HTML and CSS with no framework, build step or JavaScript dependencies, and it is served by GitHub Pages.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff)
![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?logo=githubpages&logoColor=fff)

## Contents

| Section | Anchor |
| --- | --- |
| About | `#about` |
| Technical skills | `#skills` |
| Selected projects | `#projects` |
| Experience | `#experience` |
| Contact | `#contact` |

The CV is at [`Ian_Ohuru_CV_2026.pdf`](Ian_Ohuru_CV_2026.pdf).

## Implementation

- One `index.html` with inline CSS, so the page loads in a single request
- Responsive layout with breakpoints from 900px down to 480px
- Semantic sections and in-page anchor navigation

## Local preview

```bash
python -m http.server 8000   # http://localhost:8000
```

Pushing to `main` redeploys the site through GitHub Pages.
