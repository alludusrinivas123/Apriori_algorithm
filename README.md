# Apriori Algorithm:

The Apriori algorithm is a classic data mining algorithm used to find frequent itemsets and association rules from a big pile of transactional data (like shopping carts, for example).
In simple words:
It figures out what stuff tends to be bought together.

How it works:
1.	Scan the data and find items that appear a lot (above a minimum support threshold).
2.	Make combos (pairs, triples, etc.) of these frequent items.
3.	Scan again to see which combos happen often enough.
4.	Repeat making bigger and bigger combos until no more frequent sets are found.
5.	Create "rules" like "if you buy bread 🍞, you're likely to also buy butter" with a measure called confidence.

   
Cool Example:
•	Many people buy milk  and bread 🍞 together.
•	Then you discover they also often buy butter  along with that.
•	So you can suggest butter when someone buys milk and bread!


Key concepts it uses:
•	Support: How often an itemset appears.
•	Confidence: How often a rule is true.
•	Lift: How much more likely items are bought together compared to random chance.
