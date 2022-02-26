Helping customers dbt @ [dbt Labs](https://www.getdbt.com/).

## Advanced dbt topics

- [Installing really old dbt versions](https://api.github.com/gists/dd3df9b6dde44f665b63a95b765ab893)
- [Getting dbt Cloud to throw an error if a selection did not include any models](https://api.github.com/gists/57d09c7e1d4fe31e265a002d30078e3a)
- [Adding custom generic dbt tests](https://api.github.com/gists/2e65478b5ec9d6593d7f36efbf412f17)
- [Recording model run errors in a table ](https://api.github.com/gists/064106e480106b49cd337f33a765ef20)
- [Making a dbt materialization that ignores certain columns](https://api.github.com/gists/1927816bfaebcf3be91f605e9d84d215)
- [Customising the dbt-event-logging package](https://api.github.com/gists/67e35e37880e3e7c8501672e183c4d5b)
- [Overriding dbt Cloud default database / schema on CI runs](https://api.github.com/gists/759d8675f9b36abfa8ba462c32f7c3e3)
- [Creating jobs with the dbt Cloud API](https://api.github.com/gists/38f7025e1c3aa07fe5d0631c5c6fe222)
- [Customising dbt snapshots](https://api.github.com/gists/7da6a6a4fd6dba598c04c431f74e91c0)
- [dbt SCD-2 models with stock incremental model](https://api.github.com/gists/3a23f3fbcb72f10a17fc4d31b8a47854)


## Updating this readme

The source of this README.md file is in `src/README.md` and it has to run through [`cog`](https://nedbatchelder.com/code/cog) to automatically generate the list of linked writings above.

```sh
git clone https://github.com/jeremyyeo/jeremyyeo.git
pip install cog requests
cog -o README.md -d src/README.md
```
