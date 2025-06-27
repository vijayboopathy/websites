# Personal Website

This is a personal website built with Hugo and the PaperMod theme.

## Getting Started

### Prerequisites

Make sure you have [Hugo](https://gohugo.io/getting-started/installing/) installed.

### Local Development

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-name>
    ```
2.  Run the Hugo development server:
    ```bash
    hugo server
    ```
    Your site will be available at `http://localhost:1313/`.

### Building the Site

To build the static site, run:

```bash
hugo
```

This will generate the static files in the `public/` directory.

## Deployment

This site is configured for deployment with Netlify. Simply push your changes to the `main` branch of your GitHub repository, and Netlify will automatically build and deploy your site.

## Maintenance

### Updating Hugo

Refer to the [Hugo documentation](https://gohugo.io/getting-started/installing/) for instructions on updating Hugo.

### Updating PaperMod Theme

If you have the theme as a Git submodule, you can update it by running:

```bash
git submodule update --remote --merge
```

## Customization

Custom CSS can be added to `assets/css/custom.css`.
