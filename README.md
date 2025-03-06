Developed a personalized movie recommendation system using the MovieLens dataset. Achieved a 10x improvement in recommendation accuracy over the baseline, as measured by the NDCG score.

Steps:
1. Loaded and preprocessed the MovieLens dataset, establishing vocabularies for user and movie IDs to facilitate model input.
2. Organized user interactions into sequential data, reflecting historical interaction patterns for more dynamic recommendations.
3. Designed and implemented a Transformer model integrating a positional encoder to effectively handle sequential data.
4. Employed a custom training loop, leveraging DataLoader for efficient batch processing and optimized GPU usage.
5. Employed the NDCG metric for quantitative assessment.
