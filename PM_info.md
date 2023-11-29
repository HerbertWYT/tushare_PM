# 修改时间 2023/11/29

## 内容

- 1 原代码中 “from pandas.compat import StringIO” 修改为 “from io import StringIO”
- 2 Pandas 以不再使用df.append方式进行拼接，统一更改为pd.concat