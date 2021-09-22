## Development of algorithm for classification smoking status from unstructured bilingual electronic health records based on natural language processing

### Introduction
- This repository contains smoking-related keywords extracted in the paper "Development of algorithm for classification smoking status from unstructured bilingual electronic health records based on natural language processing"
- For more information about the work, please refer to [our paper](https://www.mdpi.com/2076-3417/11/19/8812) or feel free to contact the corresponding author.

### Contents
- ```seed_words.txt``` : a list of keywords used as initial seed inputs. It is delimited by ,. The number that follows after the comma represents the label of the initial seed keywords (1=never smoker, 2=past smoker, 3=current smoker).
- ```never_smoker_keywords.txt```: a list of extracted keywords associated with never smokers.
- ```past_smoker_keywords.txt```: a list of extracted keywords associated with past smokers.
- ```current_smoker_keywords.txt```: a list of extracted keywords associated with current smokers.


### Number of keywords

|**# of keywords**| **Never Smoker** | **Past Smoker** | **Current Smoker**|
|-----:| :----------: | :--------: | :--------: |
|**Total**|  11 | 63   | 159 |
|**English**|6  | 33 | 36 |
|**Korean**| 3| 25 | 89|
|**Mixed**| 2 | 5 | 34|

- 12 keywords belong to both past smoker and current smoker classes ('positive pyr', 'p y', 'pack yrs', 'yo ppd', '넘게 갑', '계속 갑', '개피 x', 'p yr', '일에 갑', '담배 를', '대부터', '년전 ppd')

### Acknowledgments

This research was supported by a grant no 04-2019-0250 from the Seoul National University Hospital Research Fund.
