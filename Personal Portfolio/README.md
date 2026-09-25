# HTML5 Semantic Structure & Accessibility

## Project objective

This project is a multi-page personal portfolio for Sandesh Gautam. It demonstrates modern semantic HTML5 structure and practical WCAG accessibility techniques without JavaScript or advanced CSS.

## Technologies used

- HTML5 semantic elements
- Minimal CSS3 for readability and responsive layout
- No JavaScript or external dependencies

## Pages created

- `index.html` - home page with introduction, skills overview, and featured projects
- `about.html` - introduction, education, skills, learning interests, and career goals
- `projects.html` - three sample student/developer learning projects
- `contact.html` - accessible contact form and contact information

## Accessibility features

- `lang="en"` on every document
- One logical `h1` per page with ordered headings
- Skip-to-main-content link
- Keyboard-accessible navigation and form controls
- Visible `:focus-visible` states
- Consistent navigation with `aria-label` and `aria-current="page"`
- Native semantic HTML used before ARIA
- Descriptive link text and meaningful image alternative text
- Explicit labels for every form control
- Required fields, email validation, and minimum lengths
- `aria-describedby` for form instructions and message guidance
- Strong text and background contrast
- Responsive layout with reduced-motion support

## SEO features

- Unique descriptive title on every page
- Unique meta description on every page
- Responsive viewport metadata
- Semantic headings and meaningful document structure
- Descriptive internal links

## How to run

Open `index.html` directly in a modern browser, or serve the folder with a local static server. For example, from the `portfolio` folder:

```text
python -m http.server 8000
```

Then open `http://localhost:8000/` in Chrome.

The contact form is a static HTML demonstration because no backend or personal email endpoint is configured. Add a trusted form-processing endpoint before using it for real messages.

## How to test with Chrome Lighthouse

1. Open the project in Chrome using a local server.
2. Open Chrome DevTools and select the **Lighthouse** panel.
3. Choose **Navigation**, the **Desktop** or **Mobile** device profile, and the **Accessibility** and **SEO** categories.
4. Select **Analyze page load**.
5. Repeat for all four pages and review any recommendations.

## Project image

`images/profile-placeholder.jpg` is a neutral placeholder and is not presented as a photograph of Sandesh.
