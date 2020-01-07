# aamas 2020 sequential advertising data

More details including the code will be revealed soon.  

## Usage

```
>>> import pandas as pd
>>> new_df = pd.read_csv("cnxh_yhh_3_users_rtp_ut_dumps_5000_public.txt", delimiter=";")
>>> new_df.head(5)
   user_id  session_id  session_time  pvtimestamp  scenario_id  adgroup_id   price  item_id  cate_leaf_id  cate_id  shop_id      pctr       cvr  ppc  pv  clk  buycnt
0        2       46281    1533959394            0            1       50700  2680.0    44453          1044       19     1462  0.016403  0.000608   55   0    0       0
1        2       16275    1533955943            0            1       33180   549.0    39642           457       19    23734  0.011567  0.001245   53   0    0       0
2        2       16275    1533955943            0            1       13974   550.0    23882          1125       37    12932  0.002844  0.000536   38   0    0       0
3        2        2746    1533792259            0            1       22126   699.0    30531          1044       19    19542  0.025184  0.000312   38   0    0       0
4        2       46281    1533959394            0            1       23837   268.0    36228          1044       19    14488  0.008874  0.000520   55   0    0       0
```
