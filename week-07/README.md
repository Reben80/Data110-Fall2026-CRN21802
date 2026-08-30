# Week 7 — Oct 14

**DATA 110: Data Visualization and Communication**

## Topics

- **Color scales** — Sequential, diverging, and qualitative palettes (Wilke, color chapter).
- **Palmer Penguins** — Adelie, Chinstrap, and Gentoo observations from the Palmer Archipelago.
- **Exploratory comparative plots** — Grouping by species, island, or sex.
- **Pair plots** — All pairwise numeric relationships in one grid, with hue for a category.

## Resources / assignment

- Wilke, [Color basics](https://clauswilke.com/dataviz/color-basics.html)
- [The untold story of palmerpenguins](https://apreshill.github.io/palmerpenguins-useR-2022/#/title-slide)
- Penguins EDA lab (posted here and on Blackboard)

Typical Seaborn starting point:

```python
sns.pairplot(penguins, hue="species", diag_kind="kde")
```

## Notes

- This folder is for Week 7 materials: notebooks, slides, datasets, and instructions.
- Add labs, readings, or assignments here as the week is updated.
- Project 1 details live in [project1/](../project1/).

---

*See the main [README.md](../README.md) for the full course schedule.*
