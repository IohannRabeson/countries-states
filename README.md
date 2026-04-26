# Full Country and State list of our planet

The repository contains a JSON file with a __complete list of the 250 countries__ of the world. Included with all states of every single country.
The format of the full list is like following:

```
[
	{
		"code2": "AT",
	    "code3": "AUT",
	    "name": "Austria",
		"name_de": "Österreich",
	    "capital": "Vienna",
		"capital_de": "Wien",
	    "region": "Europe",
		"region_de": "Europa",
	    "subregion": "Western Europe",
    	"subregion_de": "Westeuropa",
		"eu": true,
		"ewr": true,
		"schengen": true,
	    "states": [
		    {
		        "code": "B",
		        "name": "Burgenland",
		        ubdivisio
		    },
		    ...
		]
	},
	{
		"code2": "RO",
		"code3": "ROU",
		"name": "Romania",
		"name_de": "Rumänien",
		"capital": "Bucharest",
		"capital_de": "Bukarest",
		"region": "Europe",
		"region_de": "Europa",
		"subregion": "Eastern Europe",
    	"subregion_de": "Osteuropa",
		"eu": true,
		"ewr": true,
		"nato": true,
		"schengen": true,
		"bsec": true,
		"states": [
			...
		]
	},
	...
]
```

A country-element consists of:

* code2 - Country code out of 2 letters
* code3 - Country code out of 2 letters
* name - the name of the country
* capital - the name of the capital
* region - the region/continent of the country, possible values: Asia, Europe, Africa, Oceania, Americas, Polar 
* subregion - the subregion of the country inside the region, possible values: Southern Asia, Northern Europe, Southern Europe, Northern Africa, Polynesia, Middle Africa, Caribbean, South America, Western Asia, Australia and New Zealand, Western Europe, Eastern Europe, Central America, Western Africa, Northern America, Southern Africa, Eastern Africa, South-Eastern Asia, Eastern Asia, Melanesia, Micronesia, Central Asia, * states
* eu - boolean if true
* efta - boolean if true
* ewr - boolean if true
* nato - boolean if true
* schengen - boolean if true
* bsec - boolean if true
* cefta - boolean if true

* states

A state-element consists of:

* code
* name
* subdivision (can be e.g. 'London borough', 'council area', 'country', ...)

Sources for EU, EFTA, EWR, NATO, Schengen, BSEC, CEFTA:

* [EU](https://de.wikipedia.org/wiki/Liste_der_Mitgliedstaaten_der_Europ%C3%A4ischen_Union)
* [EFTA](https://de.wikipedia.org/wiki/Europ%C3%A4ische_Freihandelsassoziation)
* [EWR](https://de.wikipedia.org/wiki/Europ%C3%A4ischer_Wirtschaftsraum)
* [NATO](https://de.wikipedia.org/wiki/NATO)
* [Schengen](https://de.wikipedia.org/wiki/Schengen-Raum)
* [BSEC](https://de.wikipedia.org/wiki/Schwarzmeer-Wirtschaftskooperation)
* [CEFTA](https://de.wikipedia.org/wiki/Mitteleurop%C3%A4isches_Freihandelsabkommen)