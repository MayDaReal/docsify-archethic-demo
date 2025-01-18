# Welcome to Docsify-Archethic Demo

> **A demonstration of how to use Docsify-This with Archethic's aeHosting.**

## Introduction

This demo shows how Markdown files can be transformed into a static website with dynamic features, hosted on Archethic's aeHosting.

## Features of the Site

- Dynamic updates without redeployment.
- Clean navigation for easy exploration.
- Multi-language support (French & English).

## Deployment Process

1. Configure Docsify-This and prepare the Markdown files.
2. Deploy the generated site using aeHosting on the Archethic testnet.
3. Observe how dynamic updates work without needing manual redeployment.

## Observations

Perform relevant tests to verify dynamic updates as listed below:

| **Test Description**                                                       | **Expected Outcome**                                                                                   | **Status** |
|-----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Add a table to list tests that can be done in `home.md` and push it to the GitHub source. | The table is displayed on the browser after a refresh of the page and few minutes after the push    | ✅         |
| Add all Markdown files to manage the French version of this website, and link it accordingly. | The French version of the website is displayed after clicking on the "Français" link in the navigation menu. | ❌         |
| Modify the sidebar content in `_sidebar.md`.                                | The updated sidebar is reflected across all pages without requiring a redeployment.                  | ⏳         |
| Add more details in the "Deployment Process" section.                       | The new details are displayed as expected.                                                           | ⏳         |
| Test the responsiveness of the site after updates on smartphones.           | The site remains responsive and accessible on various devices (desktop, tablet, mobile).             | ⏳         |
| Add images to the "Deployment Process" section and push them to the GitHub source. | The images appear correctly on the site without requiring further adjustments.                       | ⏳         |
| Test navigation links in `_navbar.md` for internal and external redirects.  | All navigation links work as expected, pointing to the correct pages or external sites.              | ⏳         |
| Add a new Markdown file `results.md` and link it in `_sidebar.md`.            | The "Results" page is accessible via the sidebar, and its content displays correctly.                  | ⏳         |
| Update `index.html` to include dependencies for a new JavaScript file to manage CSS styles dynamically. | The site design updates dynamically without requiring redeployment. | ⏳         |


During the testing process, we will note:
- The efficiency of dynamic updates.
- How well Docsify-This integrates with aeHosting.

For detailed results, including advantages and limitations, please visit the [Results page](results.md).
