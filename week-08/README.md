# Week 8 — Oct 21

DATA 110: Data Visualization and Communication

Class has two parts. First, a lecture and lab on shaping a table before you plot it. Then a Project 1 workshop: the question, the data, and a draft of the report. Presentations are in Week 9.

## Topics

**Data wrangling.** The Palmer penguins table has 344 birds and 8 columns. A chart usually needs a smaller table.

- Keep the rows that pass a test. The original table stays complete.
- Keep the columns a chart needs, and sort the rows.
- Count rows that share a value, including a combination of columns.
- Add a column computed from columns that are already there.

**Project 1 workshop.** Planning, analysis, and drafting.

- A clear question, a dataset that can answer it, and an audience.
- A small set of plots that carry the story.
- A report with an introduction, the exploration, captions on the figures, and a conclusion.

## Lab

`data-wrangling-1.ipynb`

Open it in Google Colab. Upload `penguins.csv` before you run the data cell. The file name must stay `penguins.csv`. Colab forgets uploaded files when the session ends.

## Milestone

Project 1 workshop in class. Bring your question, your dataset, and whatever plots you already have. Presentations are in Week 9.

## Resources

- Lecture slides for data wrangling, posted with this week
- Lab: `data-wrangling-1.ipynb` and `penguins.csv`
- [Palmer penguins](https://allisonhorst.github.io/palmerpenguins/)
- [pandas: indexing and selecting data](https://pandas.pydata.org/docs/user_guide/indexing.html)
- Project 1 requirements and rubric: `project1/`
- GitHub project repository setup guide

## Notes

The wrangling lab is practice for the plots in the project. Choosing rows, choosing columns, counting, and computing a new column is how a draft chart gets its table.

See the main `README.md` for the full course schedule.
