# Match-Making-Matrimony
How would you create a suggestion model that accurately show the right fit for the user in a matrimony or dating site?

This Model use Jaccard Similarity which is a widely used metric for measuring similarity between sets, including in scenarios with large datasets.
## Jaccard Similarity

The Jaccard Similarity measures the similarity between two sets by comparing the size of their intersection to the size of their union. It is defined by the equation:

![Jaccard Similarity](https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Cbg_white%20%5CLARGE%20J%28A%2C%20B%29%20%3D%20%5Cfrac%7B%7CA%20%5Ccap%20B%7C%7D%7B%7CA%20%5Ccup%20B%7C%7D)

Where:
- \( A \) and \( B \) are sets.
- \( |A \cap B| \) denotes the number of elements common to both sets.
- \( |A \cup B| \) denotes the total number of distinct elements in both sets.

This metric is commonly used in data mining, information retrieval, and natural language processing to assess the similarity between documents, sets of keywords, or other data representations.

## OUTPUT

Calculated similarity between Male User and Female User 1 is 0.18

Calculated similarity between Male User and Female User 2 is 0.00

Calculated similarity between Male User and Female User 3 is 0.25

Best matches for Male User:

Female User 3 with similarity score 0.25

Female User 1 with similarity score 0.18c

![Image Alt text](https://ibb.co/55G81p7](https://i.ibb.co/XzjsW0w/Marriage-Matchmaking-Website-Process-Flow.png)


