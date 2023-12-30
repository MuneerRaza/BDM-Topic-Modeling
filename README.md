# Short Text Distance Measurement using Context-Aware Weighted Biterms (BDM)

## Summary

In the era of internet technologies, social media, and mobile devices, short texts have become a prevalent medium for communication, information search, and product reviews. Measuring the similarity between short texts is crucial for various applications such as text retrieval, topic discovery, and event detection. However, the inherent sparsity, noise, and ambiguity in short texts pose challenges to effective distance measurement. To address this, we present the **Context-Aware Weighted Biterm Method for Short Text Distance Measurement (BDM)**.

## Features

- **Corpus-wide Word Co-occurrence Information**: Exploiting advantageous corpus-wide word co-occurrence information to enrich document-level features and mitigate challenges posed by sparse short texts.

- **Biterm Extraction and Topic Modeling**: Utilizing a novel approach to extract biterms (word pairs) from short text corpora and employing a biterm topic model to determine global weights for these biterms in the corpus.

- **Context-Aware Weighting**: Determining the local importance of a biterm in different contexts (short texts) based on the corpus-level biterm weight. This context-aware weighting enhances the accuracy of distance measurement.

- **Distance Computation**: The proposed BDM calculates the distance between two short texts using context-aware weighted biterms, providing a more accurate and effective measure of similarity.

## Implementation

This project is an implementation of the research paper titled "Short Text Similarity Measurement using Context-Aware Weighted Biterms" by Shuiqiao Yang, Guangyan Huang, Bahadorreza Ofoghi, and John Yearwood. The BDM algorithm, as described in the paper, has been implemented and tested on three real-world datasets.

## Usage

1. **Data Preparation**: Ensure your short text data is prepared in a suitable format.

2. **Biterm Extraction and Modeling**: Run the BDM algorithm to extract biterms and determine their weights using the provided short text corpus.

3. **Distance Measurement**: Calculate the distance between short texts using the context-aware weighted biterms to obtain a more accurate measure of similarity.

## Results

Experimental results on AI tool Clustering Dataset to demonstrate the superiority of the proposed BDM in terms of accuracy and effectiveness in short text distance measurement.

## Citation

If you use or find this implementation useful, please consider citing the original research paper:

```
Short text similarity measurement using context-aware weighted biterms
Shuiqiao Yang, Guangyan Huang, Bahadorreza Ofoghi, John Yearwood
```

## Acknowledgments

Special thanks to the authors of the original paper for their valuable contribution to the field of short text similarity measurement.

