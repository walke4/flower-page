# Flower Page

This exercise is a major step forward in the course. Up to this point, the coding exercises have focused on individual pages, basic HTML structure, simple CSS rules, and smaller layout ideas. In this project, you'll begin turning those skills into a more complete website layout.

The Flower Page is the first exercise where the finished result should start to look like a “real” website. You will work with a homepage that includes a wrapper, header, navigation bar, main content area, two-column layout, image highlights, and footer. You will also use one external CSS file to style multiple pages in the site.

Although this site contains multiple pages, your main job in this exercise is to build and style the homepage. The other pages are already coded for you so the navigation can work like a real website.

---

## Use Canvas for the Full Assignment Instructions

Canvas has the full assignment description, screencast videos, due date, and submission instructions.

This README is here to explain the project, remind you of the major concepts, and help you check your work before submitting.

Follow the Canvas instructions and watch the screencast videos in order.

---

## Important GitHub Workflow

This assignment uses a GitHub template repository.

You are not downloading a ZIP file for this exercise.

Instead, you will:

1. Create your own repository from my template repository.
2. Clone your copy to your computer using GitHub Desktop.
3. Open the project folder in Visual Studio Code.
4. Complete the Flower Page homepage exercise.
5. Commit your changes in GitHub Desktop.
6. Push your changes to GitHub.
7. Publish the site using GitHub Pages.
8. Add the published GitHub Pages link to the About section of your repository.
9. Submit the URL of your GitHub repository in Canvas.

The submitted Canvas link should be the **repository** URL, not the published GitHub Pages website URL.

---

## Why This Is a WebSITE, Not Just a WebPAGE

Earlier in the course, assignments focused on one HTML file at a time. This project is different because it is a small website.

A website is made of **multiple** pages that share a consistent structure, style, and navigation system.

In this project, the site includes a homepage and several interior pages. Because of that, we use an **external CSS** file. Instead of writing the same CSS rules separately on every page, all of the pages can connect to one shared stylesheet.

That is much more efficient and much easier to maintain.

If you change things in the shared CSS file, every page connected to that file will update at once.

---

## The Big Idea: Build the Boxes First

A major part of this exercise is thinking about the page as a set of boxes.

The finished homepage has several important page areas:

- a wrapper around the entire visible page
- a header at the top
- a navigation bar
- a main content area
- a left column
- a right column
- a footer at the bottom

Once those boxes exist in the HTML, CSS can style and position them.

This is an important web design process:

**First, think about the structure.**

**Then, style the structure.**

---

## HTML Structure You Will Add

In the homepage, you will add several container elements.

### Wrapper

The wrapper is a generic container around the visible page content. It is usually created with a `<div>` because it does not have a special semantic meaning by itself.

The wrapper helps control the width and placement of the page's content.

### Header

The `<header>` element is a visible page area near the top of the page.

It often contains the site name, logo, tagline, or introductory branding.

Do not confuse `<header>` with `<head>`.

The `<head>` element contains information for the browser itself.

The `<header>` element contains visible page content for visitors to see.

### Navigation

The `<nav>` element identifies the navigation area of the site.

In this project, the navigation menu is based on an unordered list. That may seem strange at first, but it is semantically correct. A navigation menu is a list of links to pages in the site.

CSS will make that list look like a horizontal navigation bar.

### Main

The `<main>` element contains the main content of the page.

Most pages should have one main content area.

### Sections

Inside the main content area, you will create several `<section>` elements for the left and right columns.

The left column contains the main flower-of-the-week content.

The right column contains flower highlight content.

### Footer

The `<footer>` element appears near the bottom of the page.

It often contains copyright information, fine print, contact information, or secondary site information.

---

## CSS Layout Concepts

This exercise introduces more advanced CSS layout techniques.

### Wrapper Layout

The wrapper limits the page width and centers the layout in middle of the browser window. A common pattern is to give the wrapper a maximum width and use automatic margins to center it.

### Background Styling

You will style the page background and wrapper background to help separate the website content from the browser window.

You will also use a background image in the header area.

### Navigation Bar

The navigation starts as a normal unordered list. With CSS, it becomes a horizontal navigation bar.

This is a good example of how HTML and CSS work together:

- HTML provides a meaningful list of links.
- CSS changes how that list looks.

### CSS Grid

You will use CSS Grid to create the main two-column layout.

CSS Grid is a modern layout tool that makes it easier to create rows and columns.

In this exercise, the main content area will be split into a left column and a right column.

You will use fractional units such as `fr` to control how much space each column receives.

For example, equal columns might use:

- `1fr 1fr`

A wider left column and narrower right column might use:

- `3fr 1fr`

The exact numbers control the relationship between the columns.

### Flexbox

You will also use Flexbox in the right column.

Flexbox is another modern layout tool. It is especially useful for arranging and aligning items in one direction.

In this exercise, Flexbox helps organize the flower highlight figures in the right column.

### Responsive Image Rule

You will add a global image rule such as:

- `max-width: 100%;`

This helps images shrink when their containers get smaller.

That does not make the whole site fully responsive yet, but it is an important step toward safer, more flexible image behavior.

---

## Design Concepts in This Exercise

This exercise also reinforces several visual design principles.

### Contrast

Contrast helps separate important content from less important content.

You will use contrast through color, size, spacing, and background choices.

### Repetition

Repetition helps a site feel consistent.

For example, repeating the same color in the navigation bar and footer can help visually connect the top and bottom of the page.

### Alignment

Alignment helps the page feel organized.

The wrapper, columns, navigation, and footer all help create a stronger layout structure.

### Proximity

Proximity means related items should appear near each other.

Figures, captions, column content, and navigation links all depend on spacing and grouping.

### Visual Hierarchy

Visual hierarchy helps visitors understand what to look at first.

Large headings, header styling, column balance, and smaller footer text all affect hierarchy.

---

## GitHub Pages

For this exercise, you will also publish the repository using GitHub Pages.

GitHub Pages turns your repository into a live website that can be viewed in a browser.

This is different from the repository itself.

The repository stores your code.

GitHub Pages displays the website created from that code.

After you publish the site, add the GitHub Pages link to the About section of your repository. That makes it easy to find the live version of your project when viewing the repo.

Remember: submit the repository URL in Canvas, not just the published site URL.

---

## GitHub Workflow Reminder

This assignment uses GitHub instead of a ZIP submission.

That means your work must be committed and pushed before your instructor can see it.

The basic workflow is:

1. Make changes in VS Code.
2. Save your files.
3. Open GitHub Desktop.
4. Review the changed files.
5. Write a short commit message.
6. Commit the changes.
7. Push the changes to GitHub.

Saving updates the files on your computer.

Committing records a checkpoint in Git.

Pushing uploads that checkpoint to GitHub.com.

If you forget to push, the repository on GitHub may not show your latest work.

---

## Before You Submit

Before submitting your work in Canvas, check the following:

- You created your own repository from the instructor template
- You cloned your repository to your computer
- You opened the full project folder in VS Code
- You worked on the homepage file, `index.html`
- The other pages are still present in the project folder
- Your HTML includes the wrapper, header, nav, main, sections, and footer
- Your navigation links work
- Your external stylesheet is linked correctly
- Your CSS styles the body and wrapper
- Your header is styled
- Your navigation bar is styled
- Your main content uses a two-column layout
- Your left column is styled
- Your right column is styled
- Your figures, images, and captions are styled
- Your footer is styled
- Your images behave safely when the browser window is resized
- Your site looks correct when opened in a browser
- You committed your changes in GitHub Desktop
- You pushed your changes to GitHub
- You published the site with GitHub Pages
- You added the GitHub Pages link to the About section of your repository
- You are submitting the repository URL in Canvas

---

## What to Submit

Submit the URL of your GitHub repository in Canvas.

Do not submit a ZIP file.

Do not submit only the GitHub Pages URL.

Your Canvas submission should look something like:

- `https://github.com/your-username/flower-page`

The GitHub Pages URL should be added to the About section of the repository, but the repository URL is what should be submitted in Canvas.

---

## Repository URL vs. Published Website URL

For this exercise, you will end up with two different URLs.

### Repository URL

The repository URL shows your code on GitHub.

It will look something like this:

- `https://github.com/your-username/flower-page`

This is the URL you submit in Canvas.

### GitHub Pages URL

The GitHub Pages URL shows the live published website.

It will look something like this:

- `https://your-username.github.io/flower-page/`

This is the URL you should add to the About section of your GitHub repository.

Do not submit only the GitHub Pages URL in Canvas. The published site is useful, but the repository is what your instructor needs to grade your code.

---


## Troubleshooting Tips

If something is not working, check these common issues first.

### My CSS is not changing the page

Check:

- Did you save the CSS file?
- Is the CSS file linked correctly in the HTML?
- Is the file name spelled correctly?
- Is the CSS file in the folder your link expects?
- Did you forget a semicolon?
- Did you forget a closing curly brace?
- Is your selector spelled correctly?

### My navigation links do not work

Check:

- Are the file names spelled correctly?
- Do the links point to the correct HTML files?
- Are all the HTML files still in the project folder?
- Did you accidentally rename or move one of the pages?

### My layout is not becoming two columns

Check:

- Did you add the left and right column sections correctly?
- Did you add the correct class names?
- Did you apply CSS Grid to the correct parent element?
- Did you define the grid columns?
- Did you save and refresh the browser?

### My right column content is not spacing correctly

Check:

- Did you apply Flexbox to the correct container?
- Did you set the flex direction correctly?
- Did you use the correct alignment or spacing property?
- Did you accidentally apply the rule to the figures instead of the column container?

### My images are too large or get cut off

Check:

- Did you add a responsive image rule?
- Is the image inside a container that is too small?
- Did you accidentally set a fixed width that is too large?
- Did you save and refresh after changing the CSS?

### My GitHub repository does not show my latest work

Check GitHub Desktop.

You may have saved your files locally but forgotten to commit or push.

Remember:

- Save updates files on your computer.
- Commit creates a checkpoint.
- Push uploads the checkpoint to GitHub.com.

### My GitHub Pages site does not update immediately

GitHub Pages may take a little time to rebuild after you push changes.

Wait a minute or two, then refresh the published site.

Also make sure your repository includes an `index.html` file at the correct location.

---

## Final Reminder

This is one of the first exercises where your work should start looking like a complete website.

The goal is not just to make the page pretty. The goal is to understand how HTML structure and CSS layout work together.

The HTML creates meaningful page areas.

The CSS controls how those areas look and where they appear.

Once you understand that relationship, you can start building pages that feel much more intentional, organized, and professional.


