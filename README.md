# AWSDemo

A responsive, single-page personal portfolio website built with HTML,
CSS, and JavaScript. The project uses the **Dimension** template from
[HTML5 UP](https://html5up.net/).

> **Current status:** The repository contains the portfolio template and
> placeholder content. Replace the sample text, social links, and images
> with your own details before publishing it as a personal portfolio.

## Features

-   Responsive, single-page layout
-   Intro, Work, About, and Contact sections
-   Navigation between sections
-   Image content stored separately from the page markup
-   CSS styling and JavaScript behavior loaded from the `assets`
    directory
-   Contact form interface (a backend or form service is required to
    actually send messages)

## Repository structure

``` text
AWSDemo/
├── assets/       # CSS, JavaScript, fonts, and other static assets
├── error/        # Error-related files
├── images/       # Images used by the portfolio
├── index.html    # Main portfolio page
├── README.md     # Project documentation
└── DS_Store      # Metadata file; not required to run the site
```

The main HTML page references these local resources:

-   `assets/css/main.css`
-   `assets/js/jquery.min.js`
-   `assets/js/skel.min.js`
-   `assets/js/util.js`
-   `assets/js/main.js`
-   Images such as `images/pic01.jpg`, `images/pic02.jpg`, and
    `images/pic03.jpg`

Keep the relative paths intact when moving or deploying the site.

## Prerequisites

No build system or package installation is required for the basic static
site.

-   A modern web browser
-   Git, if you want to clone or update the repository
-   Python 3 (optional, for running a local web server)

## Run locally

### Option 1: Open the HTML file

1.  Clone or download the repository.
2.  Open the project folder.
3.  Open `index.html` in your browser.

### Option 2: Start a local HTTP server

From the repository root, run:

``` bash
python -m http.server 8000
```

Then open:

<http://localhost:8000>

On Windows, if `python` is not recognized, try:

``` powershell
py -m http.server 8000
```

Stop the server with `Ctrl+C`.

## Customize the portfolio

1.  **Update the page title and heading.** Edit the `<title>` and main
    heading in `index.html`.
2.  **Replace the placeholder copy.** Update the Intro, Work, and About
    sections with your biography, skills, projects, and experience.
3.  **Replace the images.** Add your own images under `images/` and
    update the corresponding image paths in `index.html`.
4.  **Update social links.** Replace placeholder `href="#"` values with
    your real profile URLs.
5.  **Configure the contact form.** The current form uses `action="#"`;
    it does not send messages to an email address or server by itself.
    Connect it to a backend or a form-handling service before relying on
    it.
6.  **Check the layout.** Test the site at desktop and mobile screen
    sizes.

## Deploy with GitHub Pages

This is a static website, so it can be hosted using GitHub Pages.

1.  Open the repository on GitHub.
2.  Go to **Settings → Pages**.
3.  Under the build/deployment settings, choose **Deploy from a
    branch**.
4.  Select the `main` branch and the repository root (`/`) as the
    source.
5.  Save the settings and wait for GitHub Pages to publish the site.

The published URL will be shown in the Pages settings. Ensure
`index.html` is at the selected publishing root and that all referenced
assets are committed.

## Troubleshooting

-   **Styles or scripts are missing:** Confirm that the `assets/`
    directory exists and that file paths and capitalization match.
-   **Images do not appear:** Check that the referenced files exist in
    `images/` and use the exact same filenames.
-   **The contact form does not send:** A visual HTML form alone does
    not provide message delivery. Configure a form endpoint or backend.
-   **The page looks different when opened directly:** Try running the
    local HTTP server described above.

## Template and license

The HTML source identifies the design as **Dimension by HTML5 UP** and
references the [Creative Commons Attribution 3.0 License (CCA
3.0)](https://html5up.net/license). Review the template's license and
attribution requirements before redistributing or modifying it.

## Repository

-   GitHub: <https://github.com/thotamohan95/AWSDemo>

------------------------------------------------------------------------

This README describes the repository structure and behavior visible in
the current `main` branch. Update it as the project evolves.
