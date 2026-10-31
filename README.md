# המדרג הלאומי בטיפוס

The Israeli national climbing rankings (boulder and lead, adults and youth), season 2026/27.

- `index.html` – the page. It computes all ranking tables in the browser from the files in `data/`.
- `data/results.json` – final place of each athlete in each ranking competition (name, club, category, place).
- `data/competitions.json` – the season calendar.
- `data/scoring.json` – points tables from the national ranking rules.
- `data/abroad.json` – points from results abroad (youth championships, world ranking).

After each competition only the files in `data/` change. No ID numbers or birth dates are stored here.
