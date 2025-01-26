# Welcome to Docsify-Archethic Demo

> **A demonstration of how to use Docsify-This with Archethic's aeHosting.**

## Introduction

This demo shows how Markdown files can be transformed into a static website with dynamic features, hosted on Archethic's aeHosting.

## Features of the Site

- Dynamic updates without redeployment.
- Clean navigation for easy exploration.
- Multi-language support (French & English).

## Deployment Process

To successfully deploy and test a Docsify-This site on Archethic's aeHosting, follow these detailed steps:

### 1. **Prepare Docsify-This and Markdown Files**
- **Install Docsify-This**: Install Docsify-This using npm by running `npm install docsify-this` in your local development environment.
- **Create Markdown Files**: Write all the necessary Markdown files (`home.md`, `results.md`, etc.) with appropriate content and structure for your site.
- **Organize Files**: 
  - Use `_sidebar.md` for navigation.
  - Use `_navbar.md` for the top menu bar.
  - Use `_footer.md` for the site footer.
- **Add Metadata**: If needed, include metadata for language support, navigation, and styling.

### 2. **Configure Docsify-This**
- **Generate an `index.html` File**:
  - Use Docsify-This to generate the `index.html` file.
  - Ensure it includes all necessary dependencies (e.g., Docsify-This scripts and CSS files).
- **Enable Plugins**:
  - Use Docsify plugins such as search, pagination, or themes for a more dynamic user experience.
  - Add plugin configurations in your `index.html`.
 
- **Explore Available Templates**:
  - To inspire your site design, check out some [popular Docsify-This templates](https://docsify-this.net/#/) that showcase diverse customization options.

### 3. **Push the Repository to GitHub**
- **Upload Files**:
  - Push all Markdown files, `index.html`, `_sidebar.md`, `_navbar.md`, and `_footer.md` to your GitHub repository.
- **Enable Docsify-This Compatibility**:
  - Include a `.nojekyll` file in the repository to ensure GitHub Pages doesn’t interfere with Docsify-This.

### 4. **Deploy to Archethic's aeHosting**
- **Upload Files**:
  - Deploy only the `index.html` and `.nojekyll` files to Archethic's aeHosting.
- **Deployment on Testnet**:
  - Use Archethic's testnet interface to upload the files.
  - Verify that the deployment is successful and the site is accessible via the provided link.

### 5. **Test Dynamic Updates**
- **Make Changes Locally**:
  - Update any Markdown file in the GitHub repository (e.g., modify `home.md` or add a new file).
- **Verify Updates**:
  - Check the deployed site after a few minutes to confirm that the changes are reflected without needing manual redeployment.

### 6. **Monitor Performance and Accessibility**
- **Responsive Design**:
  - Test the site's responsiveness on various devices (desktop, tablet, mobile).
- **Performance**:
  - Check loading speed and ensure seamless navigation.

## Observations

Perform relevant tests to verify dynamic updates as listed below:

| **Test Description**                                                       | **Expected Outcome**                                                                                   | **Status** |
|-----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|------------|
| Add a table to list tests that can be done in `home.md` and push it to the GitHub source. | The table is displayed on the browser after a refresh of the page and few minutes after the push    | ✅         |
| Add all Markdown files to manage the French version of this website, and link it accordingly. | The French version of the website is displayed after clicking on the "Français" link in the navigation menu. | ❌         |
| Modify the sidebar content in `_sidebar.md`.                                | The updated sidebar is reflected across all pages without requiring a redeployment.                  | ✅         |
| Add more details in the "Deployment Process" section.                       | The new details are displayed as expected.                                                           | ✅         |
| Test the responsiveness of the site after updates on smartphones.           | The site remains responsive and accessible on various devices (desktop, tablet, mobile).             | ✅         |
| Add images to the "Deployment Process" section and push them to the GitHub source. | The images appear correctly on the site without requiring further adjustments.                       | ⏳         |
| Test navigation links in `_navbar.md` for internal and external redirects.  | All navigation links work as expected, pointing to the correct pages or external sites.              | ⏳         |
| Add a new Markdown file `results.md` and link it in `_sidebar.md`.            | The "Results" page is accessible via the sidebar, and its content displays correctly.                  | ⏳         |
| Update `index.html` to include dependencies for a new JavaScript file to manage CSS styles dynamically. | The site design updates dynamically without requiring redeployment. | ⏳         |


During the testing process, we will note:
- The efficiency of dynamic updates.
- How well Docsify-This integrates with aeHosting.

For detailed results, including advantages and limitations, please visit the [Results page](results.md).
