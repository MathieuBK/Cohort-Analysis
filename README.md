
#  👥 Cohort Analysis App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://cohort.streamlitapp.com/)

This Cohort Analysis App calculates the `retention rate` (the percentage of active customers compared to the total number of customers, split by month). This `retention rate` is then visualized and interpreted through a heatmap.

These 	2 demos are based on the following tutorials:

---
### `Bikes` dataset App

This demo is inspired by this [Cohort Analysis Tutorial](https://github.com/maladeep/cohort-retention-rate-analysis-in-python).

<img src ="https://user-images.githubusercontent.com/27242399/174592747-596cb67e-029b-444f-aaeb-975382a4128c.png" width="400px"></img>

This dataset came from the hypothetical `Sprocket Central Pty Ltd`, a medium size bikes & cycling accessories organisation.

The data was collected from `January 1, 2017` to `December 31, 2017`, and available in `CSV` format, downloadable [here](https://www.kaggle.com/datasets/archit9406/customer-transaction-dataset).

Each row in the dataset contains information about an individual bike purchase:

- Who bought it
- How much they paid
- The bike's `brand` and `product line`
- Its `class` and `size`
- What `day` the purchase happened
- The `day` when the product was first sold

The underlying code takes those purchases and groups them into cohorts and calculates the `retention rate`, split by month, so that one can answer the question:

The underlying code groups those purchases into cohorts and calculates the `retention rate` (split by month) so that one can answer the question:

*if I'm making weekly changes to my store to get people to come back and buy more bikes, are those changes working?"*

These cohorts are then visualized and interpreted through a heatmap [powered by Plotly](https://plotly.com/python/).


---
### Process

Here are the steps we undertook to create the cohort analysis app:

1. Load the data 
2. Create the cohort 
3. Calculate the retention rate
4. Visualize and interpret the retention rate via the heatmap
 
---
### About the app

- App created using 🎈[Streamlit](https://streamlit.io/) and [Plotly Heatmaps](https://plotly.com/python/heatmaps/)
- Deployed on [Streamlit Cloud](https://streamlit.io/cloud) ☁️
---

### Questions? Comments?

Please ask in the [Streamlit community](https://discuss.streamlit.io).
