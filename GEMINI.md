# Personal Website Development Plan

This document outlines a 5-stage plan to create a simple, easy-to-maintain personal website.

## Stage 1: Foundational Setup & Technology Choice [DONE]

*   **Objective:** Establish the project structure and select the core technology.
*   **Technology:** Use a Static Site Generator (SSG) like Hugo for its speed and simplicity.
*   **Tasks:**
    1.  Install Hugo.
    2.  Create a new Hugo site using `hugo new site . --force`.
    3.  Select and install a clean, minimalist theme from [themes.gohugo.io](https://themes.gohugo.io).

## Stage 2: Initial Content & Basic Styling [DONE]

*   **Objective:** Create the main pages and apply basic styling via the chosen theme.
*   **Tasks:**
    1.  Create initial content pages using markdown:
        *   `content/about.md`
        *   `content/projects.md`
        *   `content/contact.md`
    2.  Configure the `hugo.toml` file with the site title, author name, and theme settings.
    3.  Add placeholder content to the new pages.

## Stage 3: Customization and Personalization

*   **Objective:** Tailor the website's appearance to reflect a personal brand.
*   **Tasks:**
    1.  Create a custom CSS file in `assets/css/custom.css` to override or add to the theme's default styles.
    2.  Develop a simple logo or a personalized header.
    3.  Refine the content on all pages with actual project details, biographical information, and contact methods.

## Stage 4: Deployment and Automation (CI/CD)

*   **Objective:** Publish the website and automate the deployment process.
*   **Platform:** Use Netlify for free hosting and its seamless Git-based workflow.
*   **Tasks:**
    1.  Create a new repository on GitHub and push the project.
    2.  Connect the GitHub repository to a new site on Netlify.
    3.  Configure Netlify's build settings (e.g., set the Hugo version).
        4. Set up a custom domain (optional).
        *   **Pending:** Waiting for DNS propagation of A and CNAME records for `vijay.run` to Netlify.

## Stage 5: Adding Features & Long-term Maintenance

*   **Objective:** Enhance the site with new functionality and establish a maintenance routine.
*   **Tasks:**
    1.  Add a blog section for articles or updates.
    2.  Integrate a privacy-respecting analytics service (e.g., Plausible).
    3.  Add a contact form using a service like Netlify Forms.
    4.  Create a `README.md` with instructions for future maintenance.
    5.  Schedule periodic checks (e.g., every 6 months) to update the Hugo version and theme.

## Secrets and Configuration

Throughout this project, I will require your input for certain configuration values and secrets (like API keys). I will prompt you for this information when it is needed.

Per your instruction, all secrets will be stored in a `.env` file, which will be added to the `.gitignore` to prevent accidental commits. I will never ask you to paste secrets directly into the chat.

Potential secrets include:
*   **Netlify:** Site ID or API tokens for the Netlify CLI.
*   **Third-party services:** API keys for analytics or contact forms.
