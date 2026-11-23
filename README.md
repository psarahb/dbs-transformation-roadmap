# DBS Transformation Roadmap — ISM 6346 Group 3

Crawl/Walk/Run roadmap, governance RACI and QBR dashboard for DBS Bank's 2014–2019 digital transformation.

## Naming contract

All filenames are lowercase. Pages link to each other by these exact names, so do not rename them.

| File | Owner | Contents |
|---|---|---|
| index.html | Sarah Swift (Site Editor) | About Us: team bios, target audience, benefits, novelty statement; links to the three pages below |
| roadmap.html | Sarah Swift (Roadmap Sequencer) | Crawl/Walk/Run roadmap with dependency annotations |
| raci.html | Dipendra Paudel (Governance Designer) | RACI matrix with the Accountable rationale for each row |
| dashboard.html | Derek Furman (Dashboard Designer) | QBR dashboard |

## Workflow

1. `git pull`, then `git checkout -b <page>-page` (for example `raci-page`).
2. Edit only your own file, then commit and `git push -u origin <branch>`.
3. Open a pull request and add your reviewer:
   - roadmap.html → Dipendra
   - raci.html → Derek
   - dashboard.html → Sarah
   - index.html → Derek
4. After approval, merge with a merge commit and delete the branch.
