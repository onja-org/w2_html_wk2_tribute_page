# HTML, Week 2 — Tribute Page

**Day:** 1
**Estimated time:** 2 hours
**Block:** HTML · Week 2

---

## How this lab works

```
├── lab/
│   ├── instructions.md   ← Start here. Read this first.
│   ├── index.html        ← Build your tribute page here
│   └── assets/           ← Reference screenshots
├── styles.css            ← Pre-written CSS (don't edit)
└── README.md             ← You are here
```

---

## Step 1 — Read the instructions

Open `lab/instructions.md` and read it fully before touching any code.

The instructions explain what you'll build and provide step-by-step guidance. Don't skip it — the lab will be much harder without it.

---

## Step 2 — Build your tribute page

Work through the tasks in `lab/instructions.md` in order.

Your code goes inside the `<main>` tags in `lab/index.html`. Do not modify files outside of the `lab/` directory.

---

## Step 3 — Check your work

Open `lab/index.html` in your browser and compare your page to the reference screenshots in `lab/assets/`.

When it matches the screenshots, you're done!

---

## Getting stuck

1. Re-read the relevant section of the lesson
2. Check the "Common mistakes" table in the lesson
3. Search the error message — copy it exactly into Google or your AI tool
4. Ask in the group chat — share your error message and what you've already tried
5. Escalate to your mentor only if steps 1–4 haven't resolved it

---

## This week's focus

> "Decompose real UIs into sections and understand how HTML structure reflects meaning."

---

*Block HTML · Week 2*

---

## Your task

Build a tribute page for Dr. Norman Borlaug with three semantic sections:
1. **Introduction** — A title, subtitle, featured image, and caption
2. **Timeline** — A headline and bulleted list of key life events
3. **Legacy** — A closing quote and call-to-action link

Keep all your HTML inside the `<main>` tags. The CSS is already written for you — focus on structure.

## Reference

After you're done, your page should match these screenshots:

### Section 1
![Section1]( ./assets/screenshot_1.png)

### Section 2
![Section2](./assets/screenshot_2.png)

### Section 3
![Section3](./assets/screenshot_3.png)

## Tips for success

- **Read the instructions first.** The step-by-step guide in `lab/instructions.md` tells you exactly what to build.
- **Check the reference screenshots.** Each screenshot shows what that section should look like.
- **Use the required IDs.** The CSS relies on three specific IDs: `img-div`, `img-caption`, and `headline`.
- **Build section by section.** Start with the introduction, then the timeline, then the legacy section.
- **Open in a browser.** Build your page locally and open it in a browser to see your progress.

---

## Debugging tips

If something looks wrong:
1. **Check the HTML source** — Open your file and make sure all tags are properly closed
2. **Verify the IDs** — The CSS won't work without the exact IDs: `img-div`, `img-caption`, `headline`
3. **Check the CSS path** — Make sure `index.html` links to `../styles.css` (one level up)
4. **Compare to screenshots** — Side-by-side comparison of your page vs. the reference images is the best way to spot what's missing

Remember: Debugging is like being the detective in a crime movie where you are also the murderer. 😜