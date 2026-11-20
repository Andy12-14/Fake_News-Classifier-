# DATASETS

## STRUCTURE

'''bash
 .
├──  ISOT_datasets
│   ├──  Fake.csv
│   └──  True.csv
└──  LIAR_dataset
    ├──  README
    └──  splits
        ├──  test.tsv
        ├──  train.tsv
        └──  valid.tsv
'''

##  INFOS

*LIAR :*  

**Binary mapping**. The convention for the whole project is **1 = fake, 0 = real**:

| 6-class label | binary |
|---|---|
| pants-fire, false, barely-true | 1 (fake) |
| half-true, mostly-true, true | 0 (real) |

`half-true` is the debatable case. We put it in "real" because it contains a true part; that choice must be stated in the report.

- https://huggingface.co/datasets/ucsbai/liar




*ISOT :* 

-https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/ ( link of the page ) 

-https://onlineacademiccommunity.uvic.ca/isot/wp-content/uploads/sites/7295/2023/03/News-_dataset.zip ( link to download )
