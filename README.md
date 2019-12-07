# Numeracy-600K

## Introduction
Numeral is the crucial part of in narrative, especially in financial documents. We should not only analyze the text, but also need to assay the numeric information in depth. Numeracy-600K is a dataset for testing the numeracy of machines.

## How to get the full dataset of market comments?
Please write us an email with the agreement.
Email Address: cjchen@nlg.csie.ntu.edu.tw

## Format
The Numeracy-600K dataset includes two subsets:

+ Market Comments: This dataset is collected from Reuters, and consists of "id", "UNIQUE_STORY_INDEX", "offset", "length", and "magnitude" in json format.

+ Article Titles: This dataset is collected from SpamClickBait News Dataset, and consists of "id", "title", "publish_date", "offset", "length", and "magnitude"

## Example
+ Market Comments

{

'id': 0

'UNIQUE_STORY_INDEX': '20160816085706nL3N1AX2ZW'

'offset': 52,

'length': 3,

'magnitude': 1

}


+ Article Titles

{

'id': 0

'title': '100 Most Anticipated books releasing in 2010',

'publish_date': '20100101',

'number': '2010',

'offset': 40,

'length': 4,

'magnitude': 4

}

## How to Cite the Corpus
Please cite the following paper when referring to the Numeracy-600K in academic publications and papers.

Chung-Chi Chen, Hen-Hsen Huang, Hiroya Takamura and Hsin-Hsi Chen. 2019. Numeracy-600K: Learning Numeracy for Detecting Exaggerated Information in Market Comments. In Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019), Florence, Italy.

## License
Numeracy-600K is licensed under the Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license.

The full text of market comments are owned by Refinitiv https://www.refinitiv.com/en.

The full text of article titles are prepared by Rohit Kulkarni, and under CC0: Public Domain license.
