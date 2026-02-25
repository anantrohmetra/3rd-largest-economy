# Inequality — An Open Source Data Artwork

An interactive p5.js visualization of structural inequality in India, told through data, sound, and motion.

**Open source. Free to fork, expand, and criticize.**

---

## What This Is

This project uses boid-cluster visualizations to represent the groups that make up Indian society — sorted by caste, religion, sexuality, and class. Each cluster is sized by the number of people it represents. Click any cluster to hear a chord voiced from the F# minor 7 scale and read the data behind it. Click an oppressor group to watch power relations animate in real time. Press `S` to open source links.

The project is a space to name and examine:

- **Hereditary advantage and disadvantage** — wealth, caste, and class passed down across generations, determining life outcomes before a person is born
- **Hate crime and communal violence** — documented, sourced, named
- **Economic exploitation** — the means of production concentrated in the hands of billionaires and corporations while the proletariat bears the cost of that accumulation
- **Caste** — a system that predates capitalism and intersects with it; Dalits, Adivasis, and Shudras are disproportionately poor not by accident but by design
- **Religious discrimination** — minorities targeted by majoritarian state and non-state actors
- **Gender and sexuality** — compounded marginalization at the intersection of caste, class, and identity

India is one of the most unequal countries on earth. The richest 1% own 53% of national wealth. The bottom 50% share 4.1%. 358 billionaires hold more than the combined wealth of 735 million people. This is not an anomaly — it is the logic of the system.

---

## Folder Structure

```
inequality-viz/
├── README.md                  — this file
├── RECOMMENDATIONS.md         — how to contribute new data and analysis
├── boids.html                 — entry point (open in browser)
├── sketch.js                  — all visualization + audio logic
├── assets/
│   ├── Income-Share.png
│   └── Sis-Gender_Gap.png
├── facts/
│   ├── caste/
│   │   └── caste.md           — caste hierarchy, poverty, Manusmriti, census
│   ├── religion/
│   │   └── religion.md        — communal violence, hate crimes, minority rights
│   ├── economic/
│   │   └── economic.md        — wealth inequality, GST, billionaires, hunger
│   ├── gender-sexuality/
│   │   └── gender-sexuality.md — LGBTQ+ rights, gender gap, trans rights
│   └── environment/
│       └── environment.md     — climate inequality, Adani coal, carbon emissions
└── recommendations/
    └── TEMPLATE.md            — structured template for submitting new facts
```

---

## How to Run

Open `boids.html` in any modern browser. No build step. No dependencies beyond the p5.js CDN.

---

## How to Contribute

See [RECOMMENDATIONS.md](RECOMMENDATIONS.md). You can contribute:

- New data points with sources
- New groups not yet represented
- Corrections to existing facts
- Translations
- Alternative visual encodings

All contributions must be sourced. Opinion is welcome in the framing; data must be verifiable.

---

## The Unequal Starting Line

No race is fair when the starting positions are inherited.

In India — and globally — where you begin in life is determined largely by:

- The caste you are born into (determines occupation, access to education, social capital, exposure to violence)
- The religion of your family (determines safety, legal personhood, access to state protection)
- The wealth of your parents (determines nutrition, schooling, healthcare, networks)
- Your gender and sexuality (determines bodily autonomy, inheritance rights, physical safety)
- The region you are born in (determines infrastructure, language rights, access to formal economy)

None of these are chosen. All of them compound. A Dalit child born to a landless agricultural family in rural Rajasthan starts the race kilometres behind an upper-caste child born to a salaried family in Pune — and the distance is not metaphorical. It shows up in survival rates, literacy rates, income, incarceration, and life expectancy.

This project holds that **acknowledging the starting line is the minimum requirement for honest conversation about inequality**. Meritocracy as a framework is dishonest when the conditions for merit are unequally distributed at birth.

## Citation Policy

Every fact displayed in this visualization links to a primary or secondary source. All facts in the `facts/` directory must include a citation. Unsourced claims will not be merged. If a source is paywalled, include the DOI or institutional link alongside a summary of the key finding.

## Political Position

This project is not neutral. Structural inequality is not a natural phenomenon — it is produced and reproduced by legal systems, economic arrangements, cultural norms, and violence. The system does not malfunction when Dalits go hungry or Muslims are lynched. It is functioning exactly as designed.

This project is committed to naming that clearly.

---

## License

[MIT](https://opensource.org/licenses/MIT) — use it, fork it, build on it.
