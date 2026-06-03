# SC: Designing in Code

Internal training exercises for designers who want to learn how code, AI, and design work together.

You'll make small UI changes, experiment with AI-assisted coding, and see your updates appear live in the browser.

No coding experience required.

⏱ Estimated time: 30–45 minutes

## What you'll learn

* Make simple UI changes using an AI coding assistant
* See your changes update in a real browser locally
* Navigate a simple project structure in VS Code
* Create and switch Git branches safely
* Build confidence working with code as a designer

## Before you start

Make sure you have:

* VS Code installed
* Git installed
* Claude Code installed and working
* Access to GitHub
* A terminal you can open from VS Code

If you're unsure, ask your facilitator before starting the exercises.

## Getting started

1. **Clone the repo**

   ```bash
   git clone https://github.com/choon00o/SC-designcode.git
   cd SC-designcode
   ```

2. **Open the project**

   All three exercises live in [`index.html`](./index.html).

   Open the project in VS Code and open `index.html` in your browser. You'll make all your changes in this file.

3. **Use Claude to help**

   Open a terminal, type `claude`, and press Enter.

## Bonus Exercise — Create a Branch

Before making your next change, create a new branch:

```bash
git checkout -b my-first-change
```

Check which branch you're currently on:

```bash
git branch
```

You should see:

```bash
* my-first-change
```

A branch is a safe place to experiment without affecting the main version of the project.

Now continue with the exercises below.

## Exercises

### Exercise 1 — Edit with AI

The profile card is already built. Your job is to personalise it using plain-English prompts.

**Try these prompts:**

```text
In index.html, change the name "Alex" to my name
```

```text
Change the description to something about me — I like hiking and coffee
```

```text
Change the background colour to a warm cream colour
```

```text
Make the heading green instead of blue
```

```text
Make the button red with white text
```

---

### Exercise 2 — Components

The page contains three destination cards built from the same pattern. Try adding a fourth card and modifying the layout.

**Try these prompts:**

```text
In index.html, add a new destination card with the title "Singapore" and the description "Hawker food paradise"
```

```text
Make the cards sit side by side on wider screens
```

---

### Exercise 3 — Design Tokens

All colours, spacing, and radii are defined as CSS variables in `:root` at the top of `index.html`. Changing one variable updates the whole page.

**Try these prompts:**

```text
In index.html, list all the CSS custom properties defined in :root
```

```text
Change --color-primary to #ff6600 — I want to see how tokens work
```

```text
Change --color-primary back to #0770e3
```

---

## New to coding? Use AI to help

Read [AI-GUIDE.md](./AI-GUIDE.md) first — it explains how to open Claude in your terminal and how to describe what you want.

## Repo structure

```text
index.html          # All three exercises in one file
exercises/          # Original per-exercise folders with starter/solution
resources/
  cheatsheet.md     # Quick HTML/CSS reference
  links.md          # Useful docs & tools
AI-GUIDE.md         # How to use Claude for these exercises
CLAUDE.md           # AI context read automatically by Claude
```

## During the session

* Work directly in `index.html`
* The `exercises/*/solution/` folders are there if you get stuck — try not to peek too early
* Ask questions any time — to your facilitator, or to Claude
