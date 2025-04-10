# embeddings-intro
An introduction to using embeddings in search, classification, sentiment analysis, recommendation systems, and RAG.

References:
- [Popular embedding models](https://dev.to/simplr_sh/comparing-popular-embedding-models-choosing-the-right-one-for-your-use-case-43p1)
- [Embedding techniques](https://medium.com/eni-digitalks/mastering-text-similarity-combining-embedding-techniques-and-distance-metrics-98d3bb80b1b6)

## Cosine similarity

Cosine similarity is a measure used in AI and machine learning to determine how similar two vectors are, regardless of their magnitude. It's particularly useful in text analysis and natural language processing (NLP) for comparing word or sentence embeddings.

Here's how it works:

1. **Dot Product**: Calculate the dot product of the two vectors.
2. **Magnitude**: Compute the magnitude (length) of each vector.
3. **Similarity Calculation**: Divide the dot product by the product of the magnitudes of the two vectors.

The formula for cosine similarity is:

$$\text{cosine similarity} = \frac{\mathbf{A} \cdot \mathbf{B}}{\|\mathbf{A}\| \|\mathbf{B}\|}$$

Where:
- $\(\mathbf{A}\)$ and $\(\mathbf{B}\)$ are the vectors.
- $\(\mathbf{A} \cdot \mathbf{B}\)$ is the dot product of the vectors.
- $\(\|\mathbf{A}\|\)$ and $\(\|\mathbf{B}\|\)$ are the magnitudes of the vectors.

Cosine similarity ranges from -1 to 1:
- **1** indicates that the vectors are identical.
- **0** indicates that the vectors are orthogonal (no similarity).
- **-1** indicates that the vectors are diametrically opposed.

It's widely used because it focuses on the orientation of the vectors rather than their magnitude, making it ideal for comparing text data where the length of the text can vary.

Would you like to see an example of how cosine similarity is applied in a specific context?
