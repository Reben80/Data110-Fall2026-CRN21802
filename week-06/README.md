# Week 6 — Oct 7

**DATA 110: Data Visualization and Communication**

## Topics

- **Many distributions at once** — Twelve months of daily mean temperature in Lincoln, Nebraska, 2016. There are 366 days.
- **Why one panel fails** — Overlapping and stacked densities hide the months. Small multiples are readable, and hard to compare.
- **Boxplots and violins** — The box is the middle half, the line is the median, and a dot is a real day beyond the fence. A violin is a density turned sideways and mirrored. The mirror is not two groups.
- **Every day, and one row per month** — A strip chart is one dot per day, nudged sideways only. A sina plot lets the dots follow the violin. A ridgeline is one density per month. Bandwidth is the width of each day’s bell, in degrees.

## Look at these

These are short visits, not the lecture.

- [WTF Visualizations](https://viz.wtf/) — misleading graphs: truncated axes, a series cut to fit a story, decoration that changes the shape.
- [Spurious correlations](https://www.tylervigen.com/spurious-correlations) — a strong correlation is not a cause.
- Suggested viewing: [Shut up about the y-axis](https://www.youtube.com/watch?v=14VYnFhBKcY)

## Resources / assignment

- Wilke, [Chapter 9: Visualizing many distributions at once](https://clauswilke.com/dataviz/boxplots-violins.html)
- Lab: `visualizing-distributions-2.ipynb`, posted here and on Blackboard. Upload `lincoln_temps.csv` in Colab before you run the data cell. The file has one row per day: `date`, `month`, `month_long`, and `mean_temp` in °F.

Project 1 details live in [project1/](../project1/). Week 8 is the development workshop; Week 9 is presentation day.

## Notes

- This folder is for the Week 6 slides, the lab notebook, and `lincoln_temps.csv`.

---

*See the main [README.md](../README.md) for the full course schedule.*
