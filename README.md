# Section1-Sprint

`자주 쓰는 라이브러리`
- import pandas as pd
- import scipy.stats as st
- from scipy.stats import t
- import pandas as pd
- import numpy as np
- import random
- import matplotlib.pyplot as plt
- import seaborn as sns
- from scipy.stats import shapiro

`시각화에서 응용가능한 것`

 for value in top100_platform['Sales_sum']:
     top100_platform_sales.text(x=value + 5, y=cnt, s=str(round(value,2)), color='black', size=10)
     cnt+=1

`필러를 통해 데이터를 잡는법`
- 액션 장르의 데이터를 뽑는 

Genre_filter = (df.Genre == 'Action') # 조건식 작성

df_action = df.loc[Genre_filter].reset_index(drop = True)
