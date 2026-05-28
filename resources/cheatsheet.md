# Cheatsheet

## Git essentials

```bash
git clone <url>        # copy a repo locally
git status             # see what's changed
git add .              # stage all changes
git commit -m "msg"    # save a snapshot
git push               # send to GitHub
git pull               # get latest from GitHub
```

## CSS custom properties (design tokens)

```css
/* Define */
:root {
  --color-primary: #0770e3;
  --spacing-md: 16px;
}

/* Use */
button {
  background: var(--color-primary);
  padding: var(--spacing-md);
}
```

## HTML structure reminder

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Page title</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <!-- content here -->
  </body>
</html>
```
