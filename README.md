# Lab 7 - Itai Lavi

## Expose:
### Question 1

### Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

1. Within a Github action that runs whenever code is pushed
2. Manually run them locally before pushing code
3. Run them all after all development is completed

I would place the automated tests inside a GitHub Action that runs whenever code is pushed to allow bugs and broken functionality to be detected automatically before ever merging or deploying code. It also helps maintain code quality throughout development instead of waiting until the end to test everything manually.


### Question 2

### Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, E2E tests the overall user workflow and interaction with the application, Not a single functions output.

### screenshot of functioning code in ScreenShots Folder

## Eplore

### Question 3

### What is the difference between navigation and snapshot mode?

Navigation mode analyzes a webpage immediately after it loads and provides an overall performance analysis of the page load process, while Snapshot mode analyzes the webpage in its current state and is mainly useful for detecting accessibility issues.

### Question 4

### Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

Based on the Lighthouse report, three ways to improve the CSE 110 shop site would be to add accessible names and labels for buttons and custom controls (Lighthouse Errors: “Buttons have an accessible name”, “Form elements have associated labels”), add alt text to images (Lighthouse Error: “Image elements have [alt] attributes ”), and improve page performance by reducing unused JavaScript/CSS and optimizing image delivery (Lighthouse errors: “Reduce unused JavaScript”, “Reduce unused CSS ”, “Improve image delivery”).

