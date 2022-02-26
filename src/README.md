Helping customers dbt @ [dbt Labs](https://www.getdbt.com/).

### Advanced dbt topics

/*[[[cog
import cog
import requests

r = requests.get("https://api.github.com/users/jeremyyeo/gists")

for _ in r.json():
    if "#dbt" in _["description"]:
        line = f"- [{_['description'].replace(' #dbt', '')}]({_['html_url']})"
        cog.outl(line)

]]]*/
//[[[end]]]


### Updating this readme

The source of this README.md file is in `src/README.md` and it has to run through `cog` to automatically generate the list of linked writings above.

```sh
git clone https://github.com/jeremyyeo/jeremyyeo.git
pip install cog requests
cog -o README.md -d src/README.md
```
