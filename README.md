# Startup Empire Tycoon

A business simulation game in a single, self-contained `index.html` — no build step,
no dependencies to install. Open the file in a browser and play.

## Play

Open `index.html` in any modern browser, or serve the folder:

```sh
npx http-server -p 8080
```

## The opening choice

You start by picking one of four first offices, and each one is a different game:

| Start | Cash | Rent | Desks | The trade |
| --- | --- | --- | --- | --- |
| 🏚️ The Garage | $82 000 | $700 | 4 | Rich and cheap, but −18% applicants and −15% hype |
| 🏢 Co-working Desk | $60 000 | $2 400 | 6 | +22% applicants and +5% sales, but it's loud (−8% output) |
| 🏙️ Downtown Loft | $38 000 | $5 600 | 8 | +30% hype, +10% sales, +5% output — on a thin treasury |
| 🌍 Remote First | $95 000 | none | 5 | No rent, −18% salaries, but −12% output and a hard desk cap |

These bonuses apply while you stay in your first office. Move to a bigger one and
you trade them for space.

## Where the budget goes

Six departments, five levels each. Every level you buy shows up in the office —
server racks, a whiteboard, a sales board, a lab bench, a sofa and a coffee machine
appear as you pay for them.

| Department | Effect per level |
| --- | --- |
| 💻 Workstations | +7% development speed |
| 🌐 Network & Servers | +6% tech points |
| 🔬 R&D Lab | +5% design & tech, +1 tech level at 3 and 5 |
| 📣 Marketing Dept | +9% hype gain, −8% campaign cost |
| 💰 Sales Floor | +8% revenue |
| 👔 People & HR | −6% salaries, +10% applicant quality |

Short of cash? **Departments → Financing** lends against your net worth, repaid at
135% over 24 months.

## The loop

1. **Design a product** — smartphone, software app, indie game or smart wearable,
   one page per pair of components, with a live preview of what you are building.
2. **Hire the team** — applicants arrive as paper CVs with a rating, traits, country
   and salary. Designers and engineers are what turn specs into a good score.
3. **Ship it** — pick a launch marketing budget, get a rating out of 10, read the press.
4. **Reinvest** — into departments, a bigger office, louder campaigns, or buy a rival outright.

## How scoring works

A product's rating compares what you built against what the market expects *that
year*. Expectations roughly double every two years, and component tiers are
era-gated (2010 silicon is not for sale in 2003), so yesterday's flagship is
tomorrow's budget phone. Team quality counts as a *rate*, not a total — dragging a
project out for a year does not make it better than the same team's focused sprint.

Research points (🎓) accumulate from R&D and from every launch, and they are what
raise your tech level and unlock the higher component tiers.

## Controls

| Key | Action |
| --- | --- |
| `Space` | Pause / resume |
| `1` `2` `3` | Game speed |
| `N` `E` `D` `M` `P` `R` | New project · Employees · Departments · Marketing · Products · Ratings |
| `Esc` | Close the current screen |

Drag the office to pan, scroll to zoom. Progress saves to `localStorage`
automatically; the company name in the corner opens settings, including sound and reset.
