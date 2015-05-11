# Global





* * *

### parseToVariable(aliasOrVariable) 

Checks to see if a string is in the aliases dictionary and returns the appropriate variable if so.

**Parameters**

**aliasOrVariable**: `string`, A string to parse into a variable string.

**Returns**: `string`, Variable string


### isNormalizable(alias) 

Returns TRUE if the alias is normalizable (as marked in the alias dictionary), otherwise, false.

**Parameters**

**alias**: , Returns TRUE if the alias is normalizable (as marked in the alias dictionary), otherwise, false.

**Returns**: `boolean`


### parseRequestStateCode(request) 

Parses the state code in a request object, converting two letter state codes to lat/lng

**Parameters**

**request**: , Object representing an api request



### parseRequestLatLng(request) 

Checks the request object for lat/lng latitude/longitude and x/y fields and moves them to the appropriate locations

**Parameters**

**request**: , Object representing an api request



## Class: ESRItoGEO
Converts ESRI JSON to GeoJSON


## Class: GEOtoESRI
Converts geoJSON to ESRI Json

### GEOtoESRI.getACSVariableDictionary(api, year, callback) 

Downloads an ACS API's entire dictionary of variables from the Census

**Parameters**

**api**: , Downloads an ACS API's entire dictionary of variables from the Census

**year**: , Downloads an ACS API's entire dictionary of variables from the Census

**callback**: , Downloads an ACS API's entire dictionary of variables from the Census


### GEOtoESRI.latLngToFIPS(lat, lng, callback) 

Converts co-ordinates to Census FIPS via the Geocoder API

**Parameters**

**lat**: `float`, Latitude

**lng**: `float`, Longitude

**callback**: `function`, Callback function


### GEOtoESRI.acsSummaryRequest(request, callback) 

Makes a request to the ACS5 Summary API. Should be used via APIRequest and not on its own, typically

**Parameters**

**request**: `object`, JSON request (see APIRequest)

**callback**: `function`, Makes a request to the ACS5 Summary API. Should be used via APIRequest and not on its own, typically


### GEOtoESRI.tigerwebRequest(request, callback) 

Makes a call to the Census TigerWeb API for Geometry.

**Parameters**

**request**: , Makes a call to the Census TigerWeb API for Geometry.

**callback**: , Makes a call to the Census TigerWeb API for Geometry.


### GEOtoESRI.APIRequest(request, callback) 

Processes a data request by looking at a JSON request

**Parameters**

**request**: `object`, The JSON object of the request

**callback**: `function`, A callback, which accepts a response parameter


### GEOtoESRI.GEORequest(request, callback) 

Example request.

**Parameters**

**request**: `object`, The JSON request

**callback**: `function`, The callback to take the response, which is geoJSON




* * *









