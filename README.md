# Zomato Restaurant Data — EDA

An exploratory data analysis of ~9,500 restaurants from Zomato across 15 countries, looking at **where** restaurants concentrate, **what** they cost and serve, and **which factors relate to higher ratings**.

## Questions answered

1. How are restaurants distributed across countries and cities?
2. How are ratings distributed, and what counts as "good"?
3. Which cuisines are most common, and which earn the best ratings?
4. Do online delivery / table booking relate to ratings and engagement (votes)?
5. Within one market (India), how does cost relate to rating?
6. Which numeric features move together?

## Key insights

- The dataset is **heavily India-weighted**, so global averages are effectively India averages — cross-country comparisons are read with care.
- Ratings cluster in the **3.0–4.0** band; a `0` rating means *not rated* and is excluded from rating stats.
- **North Indian, Chinese and Fast Food** dominate by count; some niche cuisines post the highest average ratings.
- **Online delivery** is linked to **much higher engagement** (votes).
- In India, **higher price ranges track higher ratings**, and **votes correlate with rating more than raw cost does**.

## Tech

Python, pandas, NumPy, Matplotlib, Seaborn (Jupyter Notebook)

## Files

| File | Description |
|---|---|
| `Zomato_Restaurant_EDA_Bhavesh_Meena.ipynb` | Full EDA with embedded charts (renders on GitHub) |
| `zomato.csv` | Restaurant dataset (~9,500 rows) |
| `Country-Code.xlsx` | Country-code → country-name lookup |
| `file1.json` … `file5.json` | Raw source data |

## Run it

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
jupyter notebook Zomato_Restaurant_EDA_Bhavesh_Meena.ipynb
```
