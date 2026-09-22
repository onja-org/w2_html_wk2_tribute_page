# Tribute Page

Build a tribute page with three sections. Keep everything you write inside the `<main>` tags. The CSS is already written for you.

## Reference

After you're done, your page should match these screenshots:

### Section 1
![Section1]( ./assets/screenshot_1.png)

### Section 2
![Section2](./assets/screenshot_2.png)

### Section 3
![Section3](./assets/screenshot_3.png)

## Setup

### 0. Clone the repository

`git clone <repository-url>`
`cd w2_html_tributePage`

## Required IDs

Use these IDs in your HTML — the CSS relies on them:

- `img-div` — container div for the image
- `img-caption` — caption text for the image
- `headline` — headline for the timeline section

## Instructions

### 1. Build the page one section at a time

For the sake of practicing git branch and merge, you will develop each section in a separate branch. In the end you will merge them all into a single build branch.

**Commit and push sections**

To do for each section:

`git checkout main`
`git checkout -b <your-name>-section<x>`
*develop your section*
`git add <your-file>`
`git commit -m "create section x"`
`git push --set-upstream origin <your-name>-section<x>`


**Merge your sections into your personal branch**

`git checkout main`
`git checkout -b <your-name>-main`
`git merge <your-name>-section1`
`git merge <your-name>-section2`
`git merge <your-name>-section3`

> **ⓘ Merge resolution in case of conflict:**
> 
> *Combine changes by opening the file in your editor*
> *Save your resolution*
> `git add <file>`
> `git commit -m "merge section x"`


Happy coding, and remember: Debugging is like being the detective in a crime movie where you are also the murderer. 😜