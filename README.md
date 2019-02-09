# account-audit

| Python | Jupyter Notebook |
|--------|-----|
| 3.6+   | 5.7.4 |

## Install

[Installing the Jupyter Notebook](https://jupyter.org/install)

__dependencies:__

_requirements.txt_

## Run

1. ```mkdir raw```

2. dump account exported csv files in /raw (把账户导出csv文件放入/raw文件夹中)

3. add/verify parameters in constants.py (新建/确认 constants.py 中参数)

4. ```cd $PATH/account-audit | jupyter notebook audit.ipynb```

5. re-run all and get results (重新运行全部并查看数据)

6. account.csv will be generated for further use (将会生成account.csv，以待后用)