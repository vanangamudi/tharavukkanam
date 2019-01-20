## Tamil film reviews dataset

The film reviews are collected from samayam and cineulagam websites. The dataset contains two archives *filmreviews.zip* and *untagged.zip*.

Where *filmreviews.zip* contains CSV files with just one field each. 

1. reviews.csv contains the textual content.
2. ratings.csv contains the numerical rating. 

*unrated.zip* contains review which have no ratings associated, so needs manual tagging. 

### Example Usage

One simple usage of dataset can be used to label the text to be positive and negative and such labels can be generated from the ratings. Reviews that have rating greater than 3 can be tagged positive reviews and those that are lesser than 3 can be negative reviews.

