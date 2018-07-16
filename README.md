# Regional_USmetros_comparison
Regional Planning Division research: Economic and Population dynamics of 15 major metros across the US, 2000-2017

----

A user guide for Census Data API:

## [Census Data API User Guide](https://www.census.gov/content/dam/Census/data/developers/api-user-guide/api-guide.pdf)

The Census Data API in an API that gives the public access to raw statistical data from various Census Bureau data
programs. In terms of space, we aggregate the data and usually associate them with a
certain Census geographic boundary/area defined by a FIPS code. 

### _get your API key from:_ 
https://api.census.gov/data/key_signup.html

**Recommended:** In order to keep your API key confidential, please save your API key in a .py file named **censusAPI.py** as follows:

```python
myAPI = 'XXXXXXXXXXXXXXX'
```
Then read into this notebook as in the following cell:
```python
from censusAPI import myAPI
```

### The complete list of all available datasets for the API is located here:
https://api.census.gov/data.html

