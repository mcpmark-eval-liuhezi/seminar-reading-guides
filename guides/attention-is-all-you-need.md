# Reading Guide: Attention Is All You Need (arXiv:1706.03762)

Prepared for the Advanced NLP Seminar session on sequence transduction.

## Paper Metadata

- **Title:** Attention Is All You Need
- **arXiv ID:** 1706.03762
- **Authors:** Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, Illia Polosukhin

## Section Outline (from the paper's arXiv source, down to subsection level)

1. **Introduction**
2. **Background**
3. **Model Architecture**
   - 3.1 Encoder and Decoder Stacks
   - 3.2 Attention
     - 3.2.1 Scaled Dot-Product Attention
     - 3.2.2 Multi-Head Attention
     - 3.2.3 Applications of Attention in our Model
   - 3.3 Position-wise Feed-Forward Networks
   - 3.4 Embeddings and Softmax
   - 3.5 Positional Encoding
4. **Why Self-Attention**
5. **Training**
   - 5.1 Training Data and Batching
   - 5.2 Hardware and Schedule
   - 5.3 Optimizer
   - 5.4 Regularization
6. **Results**
   - 6.1 Machine Translation
   - 6.2 Model Variations
   - 6.3 English Constituency Parsing
7. **Conclusion**
8. **Attention Visualizations** (appendix)

## Headline BLEU Figures (WMT 2014)

- **English-to-German:** 28.4 BLEU — improving over the existing best results, including ensembles, by over 2 BLEU.
- **English-to-French:** 41.8 BLEU — a new single-model state-of-the-art, after training for 3.5 days on eight GPUs.

## Discussion Notes

- Come ready to discuss the architecture and the reported translation results.
- Focus points for the seminar: the encoder-decoder stack, multi-head attention, positional encodings, the complexity comparison against recurrent and convolutional layers, and the translation and parsing results.
