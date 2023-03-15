# 🦆 `endoflife.date` database exports

Daily offline **& consolidated database dumps** of [`endoflife.date`](https://endoflife.date/).

# 🔖 Kaggle

- See [ endoflife.date database export ](https://www.kaggle.com/code/adriensales/endoflife-date-database-export/notebook) for more.

# 🚀 Quickstart

## ☝️ Prerequisite

- [✔️`duckdb`installed](https://duckdb.org/docs/installation/)

## 🕹️ Enjoy data

```shell
mkdir -p endoflife-date-exports
kaggle kernels output adriensales/endoflife-date-database-export -p endoflife-date-exports
cd endoflife-date-exports
ls -ltr
duckdb endoflife.date.duckdb -c 'select * from details;'
```
