Helping customers dbt @ [dbt Labs](https://www.getdbt.com/).

### Advanced dbt topics

- [Extracting Snowflake variant keys and mapping them to dbt vars so we can use them as column names](https://gist.github.com/4c5fb6db98a0cc3c876e718f80bb3420)
- [Maintaining the order of columns with Redshift and dbt](https://gist.github.com/c45daad12f071969604b0888b27f6488)
- [Making a macro use the same Snowflake warehouse as the model that's calling the macro](https://gist.github.com/16a38c644d6ba90e75d8d0a5ce879f34)
- [Executing stored procedures from dbt](https://gist.github.com/e64fa3e8fafb7fa21235c80ce3048efa)
- [ The difference between `--select` and `--selector` arguments in dbt commands](https://gist.github.com/1aeca767e2a4f157b07955d58f8078f7)
- [Tidying up the SQL statements dbt generates](https://gist.github.com/38e77b15abd4a873cbde085fee39e347)
- [Accessing private GitHub repositories (dbt packages) using GitHub Apps installation access tokens](https://gist.github.com/273edd90580353709f15d393a8c5c531)
- [Live tailing a dbt Cloud run using the dbt Cloud API](https://gist.github.com/234ced3b8b2cc3a528ba48a2c343748d)
- [Filtering dbt's catalog query to only relations that are used in the project](https://gist.github.com/f83ca852510956ba3f2f96aa079c43d5)
- [Hooks vs operations in dbt](https://gist.github.com/f97b6684643a9333d7901b4cefada32c)
- [Why can't I upload the run_results.json file (using dbt_artifacts) in an on-run-end hook?](https://gist.github.com/4b83c2490e1290a9bd7a5e33c8afaaaa)
- [Are dbt freshness checks expensive in Snowflake?](https://gist.github.com/9b33ae5dee456a59f800e4fcf87c74fe)
- [Making dbt use a BigQuery project that is different to our production jobs when developing in the cloud IDE](https://gist.github.com/197fc3e56c75a1530e3e69675ee9e1c8)
- [Model name validation](https://gist.github.com/5e3bae4e7a2ff6c6b554880c0d8d0e86)
- [Installing really old dbt versions](https://gist.github.com/dd3df9b6dde44f665b63a95b765ab893)
- [Getting dbt Cloud to throw an error if a selection did not include any models](https://gist.github.com/57d09c7e1d4fe31e265a002d30078e3a)
- [Adding custom generic dbt tests](https://gist.github.com/2e65478b5ec9d6593d7f36efbf412f17)
- [Recording model run errors in a table ](https://gist.github.com/064106e480106b49cd337f33a765ef20)
- [Making a dbt materialization that ignores certain columns](https://gist.github.com/1927816bfaebcf3be91f605e9d84d215)
- [Customising the dbt-event-logging package](https://gist.github.com/67e35e37880e3e7c8501672e183c4d5b)
- [Overriding dbt Cloud default database / schema on CI runs](https://gist.github.com/759d8675f9b36abfa8ba462c32f7c3e3)
- [Creating jobs with the dbt Cloud API](https://gist.github.com/38f7025e1c3aa07fe5d0631c5c6fe222)
- [Customising dbt snapshots](https://gist.github.com/7da6a6a4fd6dba598c04c431f74e91c0)
- [Building SCD-2 models using the default incremental materialization](https://gist.github.com/3a23f3fbcb72f10a17fc4d31b8a47854)


### Updating this readme

The source of this README.md file is in `src/README.md` and it has to run through [`cog`](https://nedbatchelder.com/code/cog) to automatically generate the list of linked writings above.

```sh
git clone https://github.com/jeremyyeo/jeremyyeo.git
pip install cog requests
cog -o README.md -d src/README.md
```

This is also periodically regenerated via a GitHub workflow.

_Last generated at: Feb 15, 2023 01:55:04 UTC_
