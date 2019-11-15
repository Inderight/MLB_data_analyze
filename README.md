# MLB_data_analyze
- It's the first EDA project by Inderight.
- The MLB data set was pulled from https://baseballsavant.mlb.com/statcast_search'. Ryu's data (2013-2019)
- The dataset will be analyzed using by Python packages such as numpy,pandas,matplotlib,etc.
- Next below are the explanation of pitching parameters from the dataset.
- The code importing packages are given below as well.

```
px	
pz	
start_speed	
end_speed	
spin_rate	
spin_dir	
break_angle	
break_length	
break_y	
ax	
ay	
az	
sz_bot	
sz_top	
type_confidence	
vx0	
vy0
vz0	
x	
x0	
y	
y0	
z0	
pfx_x	
pfx_z	
nasty	
zone	
code	
type	
pitch_type	
event_num	
b_score	
ab_id	
b_count	
s_count	
outs	
pitch_num	
on_1b	
on_2b	
on_3b
```
```
import warnings
warnings.simplefilter('ignore')

# 자주 사용하는 패키지를 임포트
import matplotlib as mpl
import matplotlib.pylab as plt
from mpl_toolkits.mplot3d import Axes3D
import seaborn as sns
import numpy as np
import scipy as sp
import pandas as pd
import statsmodels.api as sm
import sklearn as sk



# matplotlib 설정
mpl.use('Agg')

# seaborn 설정
sns.set()
sns.set_style("whitegrid")
sns.set_color_codes()
```



