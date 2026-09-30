# Week 5 — Sep 30

**DATA 110: Data Visualization and Communication**

## Topics

- **Histograms** — Choose the edges, then count how many ages fall in each bin. Bin width changes which groups you can see. A bin includes its left edge and stops before its right edge.
- **Density curves** — Replace each person with a small bell, add the bells, and divide by the number of people. The area under the curve is 1. The height is a share of the people per year. The tallest Titanic bar is about 139 / (756 × 5) ≈ 0.037.
- **Two groups** — An age pyramid, or separate curves whose area follows the number of people. The worksheet repeats the same plot in small panels for survival and class.
- **Titanic ages** — 756 passengers. Age is in years, so 0.17 is about two months. The lecture compares men and women. The worksheet also splits age by survival and class.

## Resources / assignment

- Wilke, [Chapter 7: Visualizing distributions](https://clauswilke.com/dataviz/histograms-density-plots.html)
- Worksheet: `visualizing-distributions-1.ipynb`, in class after the slides. In Colab, upload `titanic.csv` before you run the data cell. The same file is on Blackboard.

## Notes

- The eight ages on the histogram slide, and the five bells on the density slide, are small made-up examples for counting by hand. The Titanic table is the real data.
- Bandwidths that are too narrow follow noise. Bandwidths that are too wide hide a real group, such as the children. A density can also enter ages that never occur, such as a negative age.

---

*See the main [README.md](../README.md) for the full course schedule.*
