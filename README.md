# University of Benin Student Registration Portal — Practice Project

A responsive, frontend-only student registration portal built with **HTML, CSS and vanilla JavaScript** for recruitment exercise practice.

> **Practice project only:** This is not an official University of Benin service. Use fictional details only.

## Features

- Responsive layout for desktop and mobile
- Student registration form with required-field and email validation
- Duplicate matriculation number check
- Registration records table
- Browser-local storage so sample records remain after a refresh in the same browser
- No framework, build step, package installation, or backend required

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Fill in the form using fictional details and submit.

## Publish with GitHub Pages

1. Open this repository: https://github.com/Silvaolamide/unbRecruitment_Test_Practice
2. Click **Settings**.
3. In the left sidebar, under **Code and automation**, click **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch** as the source.
5. Select branch **main** and folder **/(root)**.
6. Click **Save**.
7. Wait a minute or two, then revisit **Settings → Pages**. GitHub will show the published site URL.

The expected URL is:

https://silvaolamide.github.io/unbRecruitment_Test_Practice/

If it does not open immediately, wait a little and refresh the Pages settings page to check deployment status. Ensure the repository is public or that your GitHub plan and organization settings support Pages for a private repository.

## What to practise explaining

- **HTML:** semantic structure, labels, input types, required fields and form controls
- **CSS:** CSS variables, grid layout, spacing, responsive breakpoints and focus styles
- **JavaScript:** event listeners, `preventDefault()`, `FormData`, validation, DOM creation, duplicate checks and `localStorage`
- **Limitations:** browser storage is not a real database and does not share records between users or devices. A production system would need a secure backend, database, authentication, authorization and server-side validation.

## Suggested timed challenge

Try rebuilding the form in 30–45 minutes without copying the existing code. Then add one feature, such as a search box, delete-record button, or a count of registrations by department.
