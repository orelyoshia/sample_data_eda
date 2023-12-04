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

At Cyentia, we use R and the Tidyverse for our work. Please do not spend more than 1 or 2 hours on this and deliver your output as a static, non-interactive notebook. When appropriate please highlight your data visualization skills. 

Overall, we're interested in analysis to support cyber risk management. For example, frequency of events, magnitude of losses per event, trends over time or per sector, anything you think may help an organiations make better decisions around the cyber risk landscape. Include your thoughts on future areas of research, if you had more time to pursue them (again, spending no more than 1-2 hours).







