Helping customers dbt @ [dbt Labs](https://www.getdbt.com/).

### Advanced dbt topics

- [Converting a dbt jinja macro to a python function for use in a python model](https://gist.github.com/jeremyyeo/617e8c8e6549bd8d0ae0814a0273bae4)
- [Debugging dbt snapshots](https://gist.github.com/jeremyyeo/7282a2e25d86fe8b449ed70e8cdf10ff)
- [Which dbt nodes respect the generate_schema_name macro?](https://gist.github.com/jeremyyeo/fcdc4e40967435c3556612b9709fdcf4)
- [Stopping dbt from auto-expanding column types](https://gist.github.com/jeremyyeo/0dc729bd090ccf0eec5bb9bce6b2859c)
- [A quick explainer of the "dbt was unable to infer all dependencies for the model" error](https://gist.github.com/jeremyyeo/e949848d035a2bd8b7560c179b0d98da)
- [How to get models to run only on local timezones if your scheduler only supports UTC](https://gist.github.com/jeremyyeo/76403ea85b74939fac75b8c5b029b6b9)
- [How to do multi-threaded / parallel operations with dbt](https://gist.github.com/jeremyyeo/b61655a3e5a52eb27640363650c79a1e)
- [How to correctly use a macro that returns a value to a hook](https://gist.github.com/jeremyyeo/7866afc4e36c1d6afb5663ca34330a82)
- [Using alternative hosts for dbt hub packages](https://gist.github.com/jeremyyeo/1dab5d07c661c94a8be0ddf56397e621)
- [Using query comments to identify how things came to be](https://gist.github.com/jeremyyeo/88dc852c142fc78af193766d13366234)
- [Freshness checking models instead of sources](https://gist.github.com/jeremyyeo/67f07c06c4cc6943838e7262728e3f7a)
- [Converting the timestamps in dbt](https://gist.github.com/jeremyyeo/21c384f251d2216f46e3b7ae1ffe725f)
- [Can dbt introspect a table created in a pre-hook if we try to query from it in the body of the model?](https://gist.github.com/jeremyyeo/4c96bfb112a084431038d6a64dd2a413)
- [What keys to use from results or graph to associate a test with a node (model/source)](https://gist.github.com/jeremyyeo/83adf1f412e5e497baef60e5ada35bf8)
- [Why it's best not to use Truthy/Falsy/Boolean types with Jinja](https://gist.github.com/jeremyyeo/e97dbc79b536e2ae4a72d734fedb1812)
- [A pattern for moving dbt vars from dbt_project.yml to macros](https://gist.github.com/jeremyyeo/06d552ee8facc8100416655ebc25d9b9)
- [Unloading new rows to a Snowflake stage with hooks](https://gist.github.com/jeremyyeo/f07dbe9a7687ffc4976e1488a8e35547)
- [Dynamically generating `where` parameters to the `dbt_utils.union_relations` macro](https://gist.github.com/jeremyyeo/81833f260b9b02960a8fe91896a0f1d3)
- [dbt Cloud Slim CI using GitHub Actions](https://gist.github.com/jeremyyeo/429067b3c64fd5854bdfb717b4f5f303)
- [Extracting Snowflake variant keys and mapping them to dbt vars so we can use them as column names](https://gist.github.com/jeremyyeo/4c5fb6db98a0cc3c876e718f80bb3420)
- [Maintaining the order of columns with Redshift and dbt](https://gist.github.com/jeremyyeo/c45daad12f071969604b0888b27f6488)
- [Making a macro use the same Snowflake warehouse as the model that's calling the macro](https://gist.github.com/jeremyyeo/16a38c644d6ba90e75d8d0a5ce879f34)
- [Executing stored procedures from dbt](https://gist.github.com/jeremyyeo/e64fa3e8fafb7fa21235c80ce3048efa)
- [ The difference between `--select` and `--selector` arguments in dbt commands](https://gist.github.com/jeremyyeo/1aeca767e2a4f157b07955d58f8078f7)
- [Tidying up the SQL statements dbt generates](https://gist.github.com/jeremyyeo/38e77b15abd4a873cbde085fee39e347)
- [Accessing private GitHub repositories (dbt packages) using GitHub Apps installation access tokens](https://gist.github.com/jeremyyeo/273edd90580353709f15d393a8c5c531)
- [Live tailing a dbt Cloud run using the dbt Cloud API](https://gist.github.com/jeremyyeo/234ced3b8b2cc3a528ba48a2c343748d)
- [Filtering dbt's catalog query to only relations that are used in the project](https://gist.github.com/jeremyyeo/f83ca852510956ba3f2f96aa079c43d5)
- [Hooks vs operations in dbt](https://gist.github.com/jeremyyeo/f97b6684643a9333d7901b4cefada32c)
- [Why can't I upload the run_results.json file (using dbt_artifacts) in an on-run-end hook?](https://gist.github.com/jeremyyeo/4b83c2490e1290a9bd7a5e33c8afaaaa)
- [Are dbt freshness checks expensive in Snowflake?](https://gist.github.com/jeremyyeo/9b33ae5dee456a59f800e4fcf87c74fe)
- [Making dbt use a BigQuery project that is different to our production jobs when developing in the cloud IDE](https://gist.github.com/jeremyyeo/197fc3e56c75a1530e3e69675ee9e1c8)
- [Model name validation](https://gist.github.com/jeremyyeo/5e3bae4e7a2ff6c6b554880c0d8d0e86)
- [Installing really old dbt versions](https://gist.github.com/jeremyyeo/dd3df9b6dde44f665b63a95b765ab893)
- [Getting dbt Cloud to throw an error if a selection did not include any models](https://gist.github.com/jeremyyeo/57d09c7e1d4fe31e265a002d30078e3a)
- [Adding custom generic dbt tests](https://gist.github.com/jeremyyeo/2e65478b5ec9d6593d7f36efbf412f17)
- [Recording model run errors in a table ](https://gist.github.com/jeremyyeo/064106e480106b49cd337f33a765ef20)
- [Making a dbt materialization that ignores certain columns](https://gist.github.com/jeremyyeo/1927816bfaebcf3be91f605e9d84d215)
- [Customising the dbt-event-logging package](https://gist.github.com/jeremyyeo/67e35e37880e3e7c8501672e183c4d5b)
- [Overriding dbt Cloud default database / schema on CI runs](https://gist.github.com/jeremyyeo/759d8675f9b36abfa8ba462c32f7c3e3)
- [Creating jobs with the dbt Cloud API](https://gist.github.com/jeremyyeo/38f7025e1c3aa07fe5d0631c5c6fe222)
- [Customising dbt snapshots](https://gist.github.com/jeremyyeo/7da6a6a4fd6dba598c04c431f74e91c0)
- [Building SCD-2 models using the default incremental materialization](https://gist.github.com/jeremyyeo/3a23f3fbcb72f10a17fc4d31b8a47854)


### Updating this readme

The source of this README.md file is in `src/README.md` and it has to run through [`cog`](https://nedbatchelder.com/code/cog) to automatically generate the list of linked writings above.

```sh
git clone https://github.com/jeremyyeo/jeremyyeo.git
pip install cog requests
cog -o README.md -d src/README.md
```

This is also periodically regenerated via a GitHub workflow.

_Last generated at: Oct 10, 2024 01:50:51 UTC_
