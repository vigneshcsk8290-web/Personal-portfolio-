# Vigneshwaran N — Personal Portfolio

A responsive, multi-page personal portfolio built for the Thiranex internship task.

## Pages
- `index.html` — Home
- `about.html` — About and education
- `projects.html` — Selected projects
- `contact.html` — Accessible contact form demo

## Run locally
Open `index.html` in a browser. For a local development server, use the VS Code Live Server extension.

## Before publishing
1. In `contact.html`, replace `your-email@example.com` with your real email address.
2. Check every personal detail and project description; edit anything that needs correction.
3. Add your own profile photo or links if you want them. The current initials avatar is decorative and does not require an image.

## Accessibility features
- Semantic HTML5 landmarks and heading structure
- Skip-to-content link
- Keyboard-visible focus indicators
- Responsive navigation with `aria-expanded` and `aria-controls`
- Explicit form labels and native required-field validation
- Live status region for assistive technology
- Reduced-motion preference support
- Descriptive page titles and meta descriptions

## GitHub Pages deployment
1. Create a GitHub repository named `thiranex-portfolio` (or another name you prefer).
2. Upload the contents of this folder to the repository root (not the ZIP file itself).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish. Your URL will look like `https://YOUR-USERNAME.github.io/thiranex-portfolio/`.

## Lighthouse check
In Chrome, open DevTools → Lighthouse, select Mobile or Desktop, and run Accessibility and SEO audits. A perfect score cannot be guaranteed on every browser/version; fix any reported issues before submitting.
