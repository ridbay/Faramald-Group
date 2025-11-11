# Faramald Group Website

A static website built with HTML, CSS, and JavaScript.

## Project Structure
- **index.html** — Homepage
- **about.html**, **contact.html** — Additional pages
- **css/** — Stylesheets
- **js/** — JavaScript files
- **img/**, **fonts/** — Assets

## Getting Started (Local Development)
You can view the site locally in any browser. For a better dev experience, run a small static server.

- Option A: Quick view
  - Open `index.html` directly in your browser.

- Option B: Static server (recommended)
  - Using Python 3:
    ```bash
    python3 -m http.server 5500
    ```
    Then visit http://localhost:5500
  - Using Node.js (npx):
    ```bash
    npx serve . -l 5500
    ```
    Then visit http://localhost:5500

## Contributing
Please follow the process below to propose changes.

1. **Create an issue**
   - Describe the problem or feature request clearly.
   - Propose a solution or approach if possible.

2. **Branching model**
   - Base branch: `main`
   - Create a feature branch: `feature/short-description`
   - For fixes: `fix/short-description`

3. **Coding guidelines**
   - Keep HTML semantic and accessible (use proper headings, alt text, labels).
   - Keep CSS modular; avoid inline styles. Prefer utility classes already present.
   - Keep JS simple, avoid global scope leaks. Name functions and variables clearly.
   - Optimize assets (images/fonts) before committing when possible.

4. **Commits**
   - Write clear, concise messages
   - Suggested format: `type(scope): summary` (e.g., `feat(nav): add sticky header`)
   - Types: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `chore`

5. **Testing your changes**
   - Run the site locally and verify pages load with no console errors.
   - Check responsiveness and obvious regressions.

6. **Pull Request**
   - Open a PR to `main`
   - Link the related issue (e.g., "Closes #12")
   - Include a brief description, screenshots/GIFs for UI changes
   - Ensure the PR remains focused and small where possible

## Environment & Tooling
- No special build tools required; it’s a static site
- Optional: Use a live-reload server or the "Live Server" VS Code extension

## Deployment
- This repo appears to deploy as a static site (e.g., via hosting like cPanel). Coordinate with maintainers for deployment steps.

## Code of Conduct
By participating, you agree to uphold a respectful and constructive environment. Consider the [Contributor Covenant](https://www.contributor-covenant.org/) as a guideline.

## License
If a license is added to the repository, contributions will be made under that license. Until then, assume all rights reserved by the repository owner unless otherwise stated.
