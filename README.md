# ComplementApi
based on another complement thing but its kinda fixed

## How do i use this "api"

You need to make a request to https://raw.githubusercontent.com/GoofyApis/ComplementApi/main/complements.json and then find the windows version you need from the json data. Heres an example of how you can get a list of the windows versions in *Python*

```python

import requests

url = "https://raw.githubusercontent.com/GoofyApis/ComplementApi/main/complements.json"
complements = requests.get(url).json()["complements"]
print(versions)

```
