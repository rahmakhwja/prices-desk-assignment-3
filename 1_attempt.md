# Week 3 — Mean vs Median: Referee’s Note

# 1. Statistics for the cleaned Week 3 dataset

| Item | Mean | Median | First price | Last price | Percentage change |
|---|---:|---:|---:|---:|---:|
| Oil B | 324.83 | 324.00 | 301.0 | 347.0 | 15.28% |
| Pulse C | 205.92 | 206.00 | 203.0 | 210.5 | 3.69% |
| Staple A | 111.17 | 111.75 | 104.0 | 117.5 | 12.98% |
| Sweetener D | 166.75 | 166.75 | 152.0 | 181.5 | 19.41% |

# Which statistic should be reported?

- **Oil B:** The mean and median are quite close. I would report the median as the main typical price because it is less affected by unusually high or low values.
- **Pulse C:** The mean and median are almost identical with a minor difference between the two, so either gives a similar picture of the typical price. I would use the median for consistency.
- **Staple A:** The median is slightly higher than the mean. I would report the median because it is less sensitive to extreme values.
- **Sweetener D:** The mean and median are both 166.75, so they give the same central value. I would report the median for consistency.

# 2. Week 2 comparison: Sweetener D with and without the flagged value

| Statistic | With flagged value (9999) | Without flagged value (9999) |
|---|---:|---:|
| Mean | 576.81 | 167.15 |
| Median | 167.75 | 167.75 |

The value 9999 was identified in the Week 2 dataset as an illustrative teaching value, not an actual PBS observation.

The comparison shows that the mean falls substantially when the flagged value is excluded, while the median remains 167.75.

# 3. Referee’s Note: Mean vs Median in Staple Prices

**O** The cleaned Week 3 teaching dataset shows that the first-to-last average price increased for all four items.

**O** Oil B increased by 15.28%, Pulse C by 3.69%, Staple A by 12.98%, and Sweetener D by 19.41%.

**O** The mean and median are close for Oil B, Pulse C, and Staple A, while both statistics are equal at 166.75 for Sweetener D.

**E** These small differences suggest that the mean and median give a similar picture of the typical price for most items in this cleaned dataset.

**O** In the Week 2 Sweetener D data, the mean was 576.81 when the flagged value of 9999 was included, compared with 167.15 when it was excluded.

**O** The median was 167.75 in both versions of the comparison.

**E** This suggests that the median can be a more representative measure of a typical price when an unusually high value is present.

**E** Changes in supply, demand, or other market conditions such as inflation could possibly help explain the price increases, but these factors were not investigated in this analysis.

**C** The available price figures do not establish what caused the increases.

**E** My recommendation is to report the median as the main measure of a typical price and include the mean as additional information, since median doesnt vary significantly even if outliers exist.

**E** Neither neighbour is automatically wrong because the mean and median describe the centre of the data in different ways, and the more suitable statistic depends on the data being analysed.

# 4. Conclusion

The Week 3 results show that the mean and median are similar for the four items in the cleaned dataset. The Week 2 comparison demonstrates how one unusually high value can greatly affect the mean without changing the median. For this reason, I recommend reporting the median as the main typical price, alongside the mean for context.

add hash 
7516f9b521ea599538897991895673b71f0f2ed6