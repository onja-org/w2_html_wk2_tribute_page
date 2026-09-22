# Tribute Page

**Estimated time: 60–90 minutes**

**Learning objectives:** Build semantic HTML structure from visual mockups and practice git branching and merging workflow.

## What you'll build

Your finished page will have three sections. Here's what each should contain:

### Section 1: Hero Image
![Section1]( ./assets/screenshot_1.png)
- A title/headline (use an `<h1>`)
- A subtitle or introductory text (a few lines describing the subject)
- The main tribute image with a caption below it (use `id="img-div"` for the container and `id="img-caption"` for the caption text)
- Use this image URL: `https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute-page-main-image.jpg`

### Section 2: Timeline
![Section2](./assets/screenshot_2.png)
- A headline (use `id="headline"`)
- A bulleted or numbered list of key events or milestones in chronological order (use `<ul>` or `<ol>` with `<li>` items)
- Each item should be a date and a brief description

### Section 3: Quote & Closing
![Section3](./assets/screenshot_3.png)
- A notable quote (use a `<blockquote>`)
- Attribution text (who said it, or a source link)
- Any closing statement or call-to-action text

## Getting started

- Keep all your HTML inside the `<main>` tags in `index.html`
- CSS is already written — don't edit `styles.css`. All the styling for elements like `h1`, `h2`, `ul`, `li`, `blockquote`, and the custom IDs below is ready to go.

------
## Required IDs

These IDs are **required** — the CSS relies on them. Use exactly these IDs for the following elements:

- **`id="img-div"`** — The `<div>` container around your main image (Section 1)
- **`id="img-caption"`** — The `<p>` or text below the image with the caption (Section 1)
- **`id="headline"`** — The `<h2>` that introduces the timeline (Section 2)

### 0. Clone the repository

`git clone <repository-url>`
`cd w2_html_tributePage`

### 1. Build the page one section at a time

You will develop each section in a **separate git branch**. This practice lets you isolate your work — if something breaks in one section, it won't affect the others until you deliberately merge them. In the end, you'll merge all three sections together into a final `<your-name>-main` branch.

**1. Commit and push sections**

To do for each section:

`git checkout main`
`git checkout -b <your-name>-section<x>`
*develop your section*
`git add <your-file>`
`git commit -m "create section x"`
`git push --set-upstream origin <your-name>-section<x>`


**2. Merge your sections into your personal branch**

`git checkout main`
`git checkout -b <your-name>-main`
`git merge <your-name>-section1`
`git merge <your-name>-section2`
`git merge <your-name>-section3`

> **ⓘ Merge resolution in case of conflict:**
> 
> If you edited the same lines in `index.html` in multiple branches, git will mark them as a conflict. Open the file in your editor and look for the `<<<<<<<`, `=======`, and `>>>>>>>` markers. Decide which version you want to keep (or combine both), delete the markers, save the file, then:
> ```
> git add index.html
> git commit -m "merge section x"
> ```
> This is a normal part of merging — don't panic!


---

## Reference: Minimal Section 1 Example

If you're not sure how to structure Section 1, here's a minimal example to get you started:

```html
<h1>Person's Name</h1>
<p>Brief introduction about the person</p>

<div id="img-div">
  <img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute-page-main-image.jpg" alt="Photo">
  <p id="img-caption">A caption describing the image</p>
</div>
```

Sections 2 and 3 are up to you — use the screenshots as your guide and make sure to use the correct IDs and semantic HTML elements (`<ul>`, `<blockquote>`, etc.).

---

Happy coding, and remember: Debugging is like being the detective in a crime movie where you are also the murderer. 😜