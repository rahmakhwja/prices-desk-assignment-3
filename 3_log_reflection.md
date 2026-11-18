AI claim |	Colour |	How I checked it |	Decision |

- Mean and median gaps are 0.83, 0.08, 0.58 and 0. |	Green |	Subtracted each median from its mean.	| Accepted

- Typical price levels differ between items. |	Green	| Compared the four means and medians.	| Accepted

- Every item's last price is higher than its first. | Green| Compared first and last prices.	| Accepted

- Percentage changes rank Sweetener D, Oil B, Staple A, Pulse C. |	Green |	Compared the four percentages.	| Accepted

- Absolute changes rank Oil B, Sweetener D, Staple A, Pulse C. | Green | Subtracted first price from last price.	| Accepted

- Oil B starts from a higher price, explaining the different rankings. | Green	| Compared its starting price with the others and checked the absolute and percentage changes.	| Accepted

- Percentage changes match the stated formula. |	Green	| Recalculated each using (last − first) / first × 100.	| Accepted

- Close means and medians suggest no extreme values are pulling the mean.	| Amber |	Close values alone cannot establish whether extreme values exist.	| Partly accepted

- Steady price rises could explain the positions of the mean and median.	| Amber	
| The table only gives first and last prices, not the path between them.	| Partly accepted

- Either mean or median describes typical prices equally well here.	| Amber	| They are close, but this is an interpretation rather than a directly proven fact.	| Partly accepted

- Median is generally safer when outliers are possible.	| Amber |	This is a general statistical principle, not something established by this table.	| Accepted with qualification

- Neither mean nor median directly answers whether prices went up.	| Green	| First-to-last change directly measures the direction of change. | 	Accepted

- First-to-last percentage change can be misleading if an endpoint is unusual.	| Amber	| This is a reasonable limitation of using only two observations.	| Accepted with qualification

- The table cannot explain why prices rose.	| Green	| No evidence about causes is provided.	| Accepted

- The table cannot show whether changes were smooth or jumpy.	| Green	| Intermediate prices are not included in the table.	| Accepted

- The table cannot show whether one city is driving changes.	| Green | 	There is no city-level breakdown in the supplied results.	| Accepted

- The data is illustrative, so real-world significance cannot be established from it.| 	Green | 	The dataset is labelled illustrative teaching data, not actual PBS observations. |	Accepted


## Confused Classmate: transcript excerpt

**Classmate:** Hey, so I don't get why the neighbours are even arguing. The mean is the typical price. That's what "average" means, right? You add everything up, divide, and that's the price you'd usually see. Why would anyone bother with the median?

**Me:** Mean, if it accounts for outliers, overstates the value of the mean, misrepresenting the data, whereas median doesn't.

**Classmate:** Hmm, I don't really follow. What do you mean it "overstates" the value? The mean uses every price, so isn't it more accurate because it doesn't leave anything out? The median only looks at the middle one and ignores the rest. And what even is an outlier? If a price really happened, it's still a real price, so why should it get less say? Can you show me with actual numbers? Like, what would go wrong with the mean?

**Me:** It means median takes out the middle value whereas in mean we sum up the entire data. So let's assume the data is 1 1 1 and then 17: the 17 is going to increase the mean's value significantly since it takes the 17 into calculation as well. 17 is the outlier, meaning the value that is significantly greater than the rest of the data. Yes, we should keep it aside for other calculations, but it misrepresents the data...

**Classmate:** Okay, the example helps. So the mean is (1 + 1 + 1 + 17) ÷ 4 = 5, and the median is 1. Fine, they're different. But now I'm confused about something else. You said the 17 "misrepresents" the data. Misrepresents *what*? The 17 is in the data, so the mean of 5 is the true average of everything. And three of the four numbers are 1, but none of them is 5 either. So why is 1 more "typical" than 5? Isn't the median just ignoring the 17 because it's inconvenient? And in a real shop, if one week the price shot up to 17, that's what people really paid that week. Why would I leave that out when telling people what the price is?

**Me:** It misrepresents the average of the data, as in it overstates it. Median is supposed to tell us the middle value, and it calculates the median only since we place the numbers from smallest to highest, which is why it is very likely the lowest or the highest value aren't considered as the median. Let's take an example of a shop and their sales: if their average sales are 1 and just one day they made 17 sales, a better predicting statement is 1 rather than 17, since 17 would lead them to expect more.

**Classmate:** Okay, that makes more sense. If a shop usually sells 1 a day and one lucky day sells 17, then expecting around 5 a day would be a bad guess. The median of 1 describes a normal day better. So the median tells you what's typical, and the mean gets pulled around by unusual days. So is the mean just wrong? My teacher made us learn it, so it must be good for something. And what if the 17 isn't a fluke and happens every few weeks? Would I still throw it out? Also, in the price table we looked at, the mean and median were almost the same for every item. Does that mean it doesn't matter which one I report there?

**Classmate:** Okay, so the mean gets pulled up by the 17 and the median doesn't. But in the price table, the mean and median were almost the same for every item. Oil B was 324.83 and 324.00, for example. So does it matter which one I report there?

**Me:** No, the mean isn't wrong, just that the median is a better representative of the data. It is good for calculations but depends on the context, and if it happens every few weeks you could still count that as sudden changes, not regular changes. They may be very similar, but it is again better to follow through with the median.

**Classmate:** Okay, I get that the mean is still useful, just not always the best picture. But now I'm stuck on the table. For Oil B the mean is 324.83 and the median is 324.00. That's less than one rupee apart. If they're basically the same number, why is the median still "better"? Wouldn't I be reporting the same thing either way? And one more thing: you said a spike that happens every few weeks is a "sudden change, not a regular one." But how many weeks does it take before it counts as regular? Is there a rule, or do you just decide?

**Me:** It suggests that the data is symmetrical and there are few to no outliers in the data that could be affecting the distance between the mean and median. The 17 would be the cause of them being different in the 1 1 1 and 17 data set since there is an outlier; however, if we were to place 2 or 3 instead of 17, the mean and median would be significantly closer, whereas if the number were 30 or 66 they would be further apart.

**Classmate:** Okay, that finally clicks. With 1, 1, 1, 2 the mean is 1.25 and the median is 1, so they're close. With 1, 1, 1, 30 the mean jumps to 8.25 while the median stays at 1. So the mean moves with how big the extreme number is, but the median only cares about the order. That means for Oil B, a gap of less than one rupee tells me nothing big is dragging the mean, so either number would give the reader about the same picture. Here's a new question, though. Could a table like that hide a problem? What if one very high price and one very low price cancelled each other out in the mean? Would I still see it from the mean and median alone?



### Reflection: Where did my first draft say more than the data allowed?

In my first draft, I made a few claims that were too broad and weren't fully supported by the data. For example, I said that the median was always a better representation of the data than the mean. However, I learned that this depends on the distribution of the data and whether there are extreme values or outliers. The mean is not necessarily wrong; it can be just as useful as the median depending on the situation.

I also initially suggested that a small difference between the mean and median meant there were few or no outliers. After discussing this further, I realised that this is not always true because a very high and a very low value can balance each other out and leave the mean and median looking almost identical.

Another mistake was assuming that unusual price changes should not be considered when analysing typical prices. I now understand that unusual values should not automatically be removed because they are still real observations. Instead, we should investigate them and decide which measure best represents the data.

Overall, I learned that I should avoid making definite claims without enough evidence. I need to consider the context, distribution and spread of the data before deciding whether the mean or median is more appropriate.