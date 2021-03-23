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

Using R, please answer the following questions:

1.  Visualize the distribution of dollars involved in breaches

2.  What is the typical loss (in dollars)?

3.  What is the relationship between total\_amounts and affected\_count?

## Parameters

-   You may use any shared document format with which you are
    comfortable. Some possible formats include a RMarkdown notebook, a
    PDF, a Google Docs, or Word document.

-   Your document submission must include both the output and the code
    used to produce the output.

-   Be prepared to walk through and discuss your document in a shared
    Zoom meeting when we meet.

-   Use any packages and libraries with which you are comfortable.

-   Have questions? Ask! We want to see your thought process, not catch
    you in any subtle traps!
