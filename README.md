Sample Data EDA
================

## Data Structure

This repository contains a `sample_breaches.csv` data file containing
cyber breach information (this is simulated data, not live customer
information). The schema for the file is:

| column                   | description                                        |
|--------------------------|----------------------------------------------------|
| id                       | Unique record identifier                           |
| affected\_count          | Number of data records involved in the breach      |
| total\_amount            | Dollar cost of the breach                          |
| naic\_sector             | Two digit NAICS code of the industry sector        |
| naic\_national\_industry | Full six-digit NAICS code for the breached company |
| sector                   | Text description of the `naic_sector` field        |
| breach\_date             | Date the breach occurred                           |
| cause                    | High level summary of the cause of the breach      |

## Questions

At Cyentia, we use R and the Tidyverse for our work. Feel free to use
another language/environment if you prefer. Please answer the following
questions:

1.  Visualize the distribution of dollars involved in breaches

2.  What is the typical loss (in dollars)?

3.  What is the relationship between total\_amounts and affected\_count?
