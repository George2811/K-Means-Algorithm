# K-Means-Algorithm

This is a Data Science project in which we want to know how to detect counterfeit bills. For this we have 1372 banknote authentication data, in these data we find variables such as the variance and skewness of a banknote.
## Now what does the variance mean?
This measures how much a bill varies from the original model. No two bills are the same, as each one has unique codes and identifiers. However, if the variance is high, it can be interpreted that this is not the only thing that has changed.
On the other hand, we have the data of skewness. The banknotes have representative images which must be as symmetrical as possible, otherwise we may be in front of a false banknote.
## Once the dataset is read, how do we analyze this data?
For this project we have used the K-Means algorithm, which allows us to group objects into k groups based on their characteristics.

Once the data have been obtained, we can conclude that there is a relationship between the variance and the skewness. In other words, the greater the variance, the greater the asymmetry and therefore the more possibilities that the bill is false. Not all the data comply with this, but we can take this measure as a preliminary supervision.
The recommendation that I would give to customers is that when receiving a ticket, the first thing that is verified is its symmetry. For this, in case of being doubtfully asymmetric, it is considered as a potential false bill, and for this, send the bill to other procedures for the confirmation of this hypothesis.
