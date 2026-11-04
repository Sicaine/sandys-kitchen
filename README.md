# Sandy's Kitchen

**Crumb & Caramel**: a falling-sand bakery and candy kitchen that runs in the browser.

Play it at **https://sicaine.github.io/sandys-kitchen/**

Every grain has a temperature, and recipes are real ratios by weight (1 grain = 1 g). You can:

- Weigh out ingredients with dispensers, then mix them in a bowl or with the whisk. It tells you what you're making, or what's missing.
- Bake in ovens with doors and Auto bake, or in a tunnel oven.
- Cook syrup through the candy stages: fudge, caramel, hard candy.
- Build lines with belts at any angle, pipes, gates, rolling pins and cookie cutters.
- Automate everything with the step program.
- Run it forever: a tin feeder supplies empty tins and a packing crate takes finished bakes off the line and counts them.
- Collect 43 entries in the recipe book.
- Pick a backdrop: slate, subway or pistachio tiles, strawberry wallpaper, wood paneling, a night window, diner checker or plain dark.

The kitchen grows to fit your window (Kitchen menu → Fit kitchen to window after resizing), and there is a fullscreen button.

Built for a desktop browser with a mouse.

## Project layout

- `site/index.html`: the whole game in one file, with no build step and no dependencies.
- `.github/workflows/pages.yml`: deploys `site/` to GitHub Pages on every push to `main`.

## GitHub Pages setup

In the repository settings, go to **Pages** and set **Build and deployment → Source** to **GitHub Actions**. After that, every push to `main` deploys automatically. You can also run the workflow by hand from the **Actions** tab.

## Run locally

Open `site/index.html` in a browser, or serve the folder:

```sh
python3 -m http.server -d site 8000
```
