# Lab: Build a Tribute Page

## What is a tribute page?

A tribute page is a web page dedicated to honoring someone's life and achievements. It uses semantic HTML to organize information into meaningful sections that tell a story about the person.

In this lab, you'll build a tribute page about **Dr. Norman Borlaug**, a scientist who saved millions of lives through agricultural innovation.

---

## Your task

Build a tribute page with **three sections**:

1. **Introduction section** — A title, subtitle, and a featured image with a caption
2. **Timeline section** — A headline and a bulleted list of key dates and events
3. **Legacy section** — A closing quote and a call to action (link)

All your code should go inside the `<main>` tags in `lab/index.html`. The CSS is already written for you — focus on the HTML structure.

---

## Required IDs

The CSS relies on these specific IDs. **Use them exactly as written:**

- `id="img-div"` — The container around the featured image
- `id="img-caption"` — The text below the image that describes it
- `id="headline"` — The heading for the timeline section

---

## Section 1: Introduction

### What it should contain:
- An `<h1>` heading with the person's name: **"Dr. Norman Borlaug"**
- A subtitle (paragraph text): **"The man who saved a billion lives"**
- A featured image (see below for the image URL)
- An image caption (see below for the caption text)

### Step-by-step:

1. **Create the heading**
   ```html
   <h1>Dr. Norman Borlaug</h1>
   ```

2. **Create the subtitle** — Use a `<p>` tag:
   ```html
   <p>The man who saved a billion lives</p>
   ```

3. **Create the image container** — Use a `<div>` with `id="img-div"`:
   ```html
   <div id="img-div">
     <!-- Image goes here -->
   </div>
   ```

4. **Add the image inside the container** — Use `<img>` tag:
   ```html
   <img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute_page/norman_borlaug.jpg" alt="Dr. Norman Borlaug" />
   ```

5. **Add the image caption** — Use a `<p>` tag with `id="img-caption"`:
   ```html
   <p id="img-caption">Dr. Norman Borlaug, third from the left, trains biologists in Mexico on how to increase wheat yields - part of his life-long war on hunger.</p>
   ```

**Visual reference:** See `screenshot_1.png` for what this section should look like.

---

## Section 2: Timeline

### What it should contain:
- A heading: **"Here's a time line of Dr. Borlaug's life:"** (with `id="headline"`)
- A bulleted list (`<ul>` and `<li>` tags) with timeline entries

### Step-by-step:

1. **Create the headline** with the required ID:
   ```html
   <h2 id="headline">Here's a time line of Dr. Borlaug's life:</h2>
   ```

2. **Create an unordered list** with timeline entries:
   ```html
   <ul>
     <li><strong>1914</strong> - Born in Cresco, Iowa</li>
     <li><strong>1933</strong> - Leaves his family's farm to attend the University of Minnesota, thanks to a Depression era program known as the "National Youth Administration"</li>
     <!-- Add more list items here -->
   </ul>
   ```

3. **Add all these timeline entries** (each as an `<li>` inside the `<ul>`):

   - **1914** - Born in Cresco, Iowa
   - **1933** - Leaves his family's farm to attend the University of Minnesota, thanks to a Depression era program known as the "National Youth Administration"
   - **1935** - Has to stop school and save up more money. Works in the Civilian Conservation Corps, helping starving Americans. "I saw how food changed them", he said. "All of this left scars on me."
   - **1937** - Finishes university and takes a job in the US Forestry Service
   - **1938** - Marries wife of 69 years Margret Gibson. Gets laid off due to budget cuts. Inspired by Elvin Charles Stakman, he returns to school study under Stakman, who teaches him about breeding pest-resistant plants.
   - **1941** - Tries to enroll in the military after the Pearl Harbor attack, but is rejected. Instead, the military asked his lab to work on waterproof glue, DDT to control malaria, disinfectants, and other applied science.
   - **1942** - Receives a Ph.D. in Genetics and Plant Pathology
   - **1944** - Rejects a 100% salary increase from Dupont, leaves behind his pregnant wife, and flies to Mexico to head a new plant pathology program. Over the next 16 years, his team breeds 6,000 different strains of disease resistant wheat - including different varieties for each major climate on Earth.
   - **1945** - Discovers a way to grown wheat twice each season, doubling wheat yields
   - **1953** - crosses a short, sturdy dwarf breed of wheat with a high-yielding American breed, creating a strain that responds well to fertilizer. It goes on to provide 95% of Mexico's wheat.
   - **1962** - Visits Delhi and brings his high-yielding strains of wheat to the Indian subcontinent in time to help mitigate mass starvation due to a rapidly expanding population
   - **1970** - receives the Nobel Peace Prize
   - **1983** - helps seven African countries dramatically increase their maize and sorghum yields
   - **1984** - becomes a distinguished professor at Texas A&M University
   - **2005** - states "we will have to double the world food supply by 2050." Argues that genetically modified crops are the only way we can meet the demand, as we run out of arable land. Says that GM crops are not inherently dangerous because "we've been genetically modifying plants and animals for a long time. Long before we called it science, people were selecting the best breeds."
   - **2009** - dies at the age of 95.

**Visual reference:** See `screenshot_2.png` and `screenshot_3.png` for what this section should look like.

---

## Section 3: Legacy (Closing)

### What it should contain:
- A blockquote (important quote about Dr. Borlaug)
- A closing sentence with a link to his Wikipedia page

### Step-by-step:

1. **Add a blockquote** after the timeline list:
   ```html
   <blockquote>
     <p>"Borlaug's life and achievement are testimony to the far-reaching contribution that one man's towering intellect, persistence and scientific vision can make to human peace and progress."</p>
     <cite>-- Indian Prime Minister Manmohan Singh</cite>
   </blockquote>
   ```

2. **Add a closing paragraph with a link**:
   ```html
   <p>If you have time, you should read more about this incredible human being on his <a href="https://en.wikipedia.org/wiki/Norman_Borlaug" target="_blank">Wikipedia entry</a>.</p>
   ```

**Visual reference:** See `screenshot_3.png` for what this section should look like.

---

## Putting it all together

Your `<main>` section should contain:
1. Section 1 (h1, subtitle, image div with caption)
2. Section 2 (headline with ID, unordered list of timeline entries)
3. Section 3 (blockquote, closing paragraph with link)

---

## How to check your work

1. Open `lab/index.html` in your browser
2. Compare your page to the three reference screenshots:
   - `assets/screenshot_1.png` — Introduction section
   - `assets/screenshot_2.png` — First part of timeline
   - `assets/screenshot_3.png` — Rest of timeline and closing
3. Make sure:
   - All text matches the screenshots
   - The image displays
   - The layout looks similar (CSS will handle styling)
   - Required IDs are in place (`img-div`, `img-caption`, `headline`)

---

## Common mistakes

| Mistake | Solution |
|---------|----------|
| Image doesn't show up | Check the `<img>` tag has a `src` attribute pointing to the correct URL |
| IDs aren't working in CSS | Check the spelling: `id="img-div"`, `id="img-caption"`, `id="headline"` (lowercase, hyphens) |
| List items don't look right | Make sure you're using `<ul>` (unordered list) and `<li>` (list items) |
| Caption text misaligned | Wrap it in a `<p>` tag with `id="img-caption"` — the CSS uses this ID |
| Styles don't load | Make sure the path to `styles.css` in your HTML is correct — it should be `href="../styles.css"` |

---

## Next steps

1. Build your HTML inside `lab/index.html`
2. Open it in a browser and compare to the reference screenshots
3. Once it matches, you're done!

Good luck! Remember: a tribute page is about telling someone's story through well-organized sections. Each section has a purpose:
- **Section 1** introduces who they are
- **Section 2** shows their achievements over time
- **Section 3** reflects on their legacy
