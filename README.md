# Repo with datasets so I fx use import them them like this in python:
Click on the dataset in your repository, then click on View Raw. Copy the link to the raw dataset
->

```
import pandas as pd

url = 'copied_raw_GH_link'
df1 = pd.read_csv(url)
# Dataset is now stored in a Pandas Dataframe
```
(As [this link](https://towardsdatascience.com/3-ways-to-load-csv-files-into-colab-7c14fcbdcb92))
