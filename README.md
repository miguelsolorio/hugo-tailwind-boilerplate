# hugo-tailwind-boilerplate
A [Hugo](https://gohugo.io) boilerplate website that uses [Tailwind](https://tailwindcss.com).
## File Structure
    
### HTML
All pages can be found under `content` which use the default layout template found under `layouts > _default`. You can also find all partials under `layouts > partial`.

### CSS
All CSS dependencies are imported at `assets > css > main.css`, which automatically adds [Tailwind](https://tailwindcss.com).

### JavaScript
All JS files are part of the `assets > js > scripts.js`  array in the gulpfile.js

## Building
Simply run `npm run develop` or if you're using VS Code, `Cmd/Ctrl + Shift + B` wil automatically run the task.