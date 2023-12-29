# 重置index为从0开始的自然增长数字，同时去掉其原index

```
import pandas as pd
import numpy as np

df = pd.DataFrame(np.random.randn(10, 5))
df2 = df.iloc[5:, :]
df2
```
![Alt text](./images/image.png)
```
df2.reset_index(drop=True)
```
![Alt text](./images/image-1.png)