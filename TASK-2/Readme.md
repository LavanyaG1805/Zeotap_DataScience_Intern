# Lookalike Model

This project implements a Lookalike Model that identifies and recommends the top 3 most similar customers based on their profile and transaction history. The recommendations are generated using a combination of customer demographics, transaction behavior, and product category preferences.

## Features

### Feature Engineering
- Customer profiles (`Region`) with one-hot encoding.
- Transaction behavior:
  - Total spend.
  - Average spend.
  - Transaction count.
  - Items purchased.
- Product category preferences (percentage spend per category).

### Similarity Calculation
- Features are standardized using `StandardScaler`.
- Pairwise cosine similarity is calculated to identify similar customers.

### Output
- A CSV file with the top 3 similar customers for the first 20 customers.
- Each record includes the `customer_id` and a list of recommendations with similarity scores.

