# Problem Definition:
Correlation between Reddit daily thread and Stock market performance - Classification problem
whether reddit comments generalise into the retail investors behaviour

## 1. Training data
### Training data - Reddit_WhatAreYourMoveTmr thread
 - WhatAreYourMoveTmr - 1Jul22-30Jun23
 - record number: 242

### Training data - Market_data
 - df_NQ_1Jul22-30Jun23.csv
 - df_SP_1Jul22-30Jun23.csv
   
## 2. Features Enginnering
- number of keywords
- keywords
- NLP scores

## 3. Label
- S&P 500 up or down (% of up/down?)
- NQ % up or down

## 4. Analysis proposal
1. rank the top 1000 keywords among 1 year comment (fixed pool of keywords)
   - build a data frame containing every day record, appreance account of the fixed pool of 1000 keywords
2. score of each keywords (adjust weighting depends on positive and negative)
