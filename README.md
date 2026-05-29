# SC: Designing in Code

Internal training — hands-on exercises for building UIs in code.

You can work through these exercises yourself, or use Claude (AI) to help make changes. No coding experience required.

## What you'll learn

- How to translate designs into code
- Working with components and design tokens
- Building consistent, scalable UI

## Getting started

1. **Clone the repo**
   ```bash
   git clone https://github.com/choon00o/SC-designcode.git
   cd SC-designcode
   ```

2. **Open the single exercise file**
   All three exercises live in [`index.html`](./index.html) at the root — open it in your browser and editor and work from there.

3. **Use Claude to help** — open a terminal, type `claude`, and press Enter.

## Exercises

### Exercise 1 — Edit with AI

The card is already built. Your job is to make it yours — using plain English prompts.

**Try these prompts:**

```
In index.html, change the name "Alex" to my name
```
```
Change the description to something about me — I like hiking and coffee
```
```
Change the background colour to a warm cream colour
```
```
Make the heading green instead of blue
```
```
Make the button red with white text
```

---

### Exercise 2 — Components

The card grid has three destination cards sharing the same structure. Try adding a new one.

**Try these prompts:**

```
In index.html, add a new destination card with the title "Singapore" and the description "Hawker food paradise"
```
```
Make the cards sit side by side on wider screens
```

---

### Exercise 3 — Design Tokens

All colours, spacing, and radii are defined as CSS variables in `:root` at the top of `index.html`. Changing one variable updates the whole page.

**Try these prompts:**

```
In index.html, list all the CSS custom properties defined in :root
```
```
Change --color-primary to #ff6600 — I want to see how tokens work
```
```
Change --color-primary back to #0770e3
```

---

## New to coding? Use AI to help

Read [AI-GUIDE.md](./AI-GUIDE.md) first — it explains how to open Claude in your terminal and how to describe what you want.

## Repo structure

```
index.html          # All three exercises in one file
exercises/          # Original per-exercise folders with starter/solution
resources/
  cheatsheet.md     # Quick HTML/CSS reference
  links.md          # Useful docs & tools
AI-GUIDE.md         # How to use Claude for these exercises
CLAUDE.md           # AI context (read automatically by Claude)
```

## During the session

- Work directly in `index.html`
- The `exercises/*/solution/` folders are there if you get stuck — try not to peek too early!
- Ask questions any time — to your facilitator, or to Claude
