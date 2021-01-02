---
title: "Home"
date: 2021-01-01T14:51:19-08:00
draft: false
menu: "main"
weight: 1
---

## File Structure
    
### HTML
All pages can be found under {{< code "content" >}} which use the default layout template found under {{< code "layouts > _default" >}}. You can also find all partials under {{< code "layouts > partial" >}}.

### CSS
All CSS dependencies are imported at {{< code "assets > css > main.css" >}}, which automatically adds [Tailwind](https://tailwindcss.com).

### JavaScript
All JS files are part of the {{< code "assets > js > scripts.js" >}}  array in the gulpfile.js

## Building
Simply run {{< code "npm run develop" >}} or if you're using VS Code, {{< code "Cmd/Ctrl + Shift + B" >}} wil automatically run the task.