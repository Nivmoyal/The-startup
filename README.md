# Startup Empire Tycoon

A business simulation game in a single, self-contained `index.html` — no build step,
no dependencies to install. Open the file in a browser and play.

![Startup Empire Tycoon](https://img.shields.io/badge/single--file-HTML5-ffb020)

## Play

Open `index.html` in any modern browser, or serve the folder:

```sh
npx http-server -p 8080
```

## The loop

1. **Design a product** — smartphone, software app, indie game or smart wearable.
   Every component (chipset, camera, art direction, sensors…) has four tiers that
   trade cost and development time against design ✎ and tech ⚡ points.
2. **Hire the team** — applicants arrive as paper CVs with a skill rating, traits,
   country and salary. Designers and engineers are what actually turn specs into a
   good score; a solo founder ships bugs.
3. **Ship it** — pick a launch marketing budget, get a rating out of 10, and read
   what the press says.
4. **Reinvest** — sales pay for bigger offices, better people and louder campaigns,
   until you can simply buy your rivals outright.

## How scoring works

A product's rating compares what you built against what the market expects *that
year*. Expectations roughly double every two years, and component tiers are
era-gated (2010 silicon is not for sale in 2003), so yesterday's flagship is
tomorrow's budget phone. Team quality counts as a *rate*, not a total — dragging a
project out for a year does not make it better than the same team's focused sprint.

## Controls

| Key | Action |
| --- | --- |
| `Space` | Pause / resume |
| `1` `2` `3` | Game speed |
| `N` `E` `M` `P` `R` `O` | New project · Employees · Marketing · Products · Ratings · Office |
| `Esc` | Close the current screen |

Drag the office to pan, scroll to zoom. Progress saves to `localStorage`
automatically; the company name in the header opens settings, including reset.
