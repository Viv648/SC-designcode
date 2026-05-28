# Exercise 3: Design Tokens

Use tokens instead of hard-coded values.

## Goal

Replace magic numbers and raw colour values with named design tokens (CSS custom properties), so that changing one value updates the whole page.

## Brief

The starter file uses hard-coded colours, spacing, and font sizes throughout. Refactor it to use CSS variables defined in `:root`.

---

## Option A — Do it yourself

1. Open `starter/styles.css`
2. Identify repeated or magic values (colours, spacing, radii)
3. Define them as CSS custom properties in `:root { }` at the top
4. Replace all hard-coded values with `var(--token-name)`

Example:
```css
:root {
  --color-primary: #0770e3;
  --spacing-md: 16px;
}

button {
  background: var(--color-primary);
  padding: var(--spacing-md);
}
```

## Option B — Use AI (Claude)

Open a terminal, type `claude`, then try:

```
Look at exercises/03-design-tokens/starter/styles.css and list all the hard-coded colour values
```

```
Replace all the hard-coded colours with CSS custom properties defined in :root
```

```
Do the same for spacing and font size values
```

```
Now change --color-primary to #ff6600 — I want to see how tokens make this easy
```

After the last step, change it back:
```
Change --color-primary back to #0770e3
```

That's the point of tokens — one change, everywhere updates.

---

## Done?

Compare your tokens against `solution/styles.css`.

> New to this? Check out [AI-GUIDE.md](../../AI-GUIDE.md) for tips on how to talk to Claude.
