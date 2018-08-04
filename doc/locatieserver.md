
## Wrapper for PDOK Locatieserver
The Dutch National SDI (PDOK) is a central facility for unlocking geodatasets of national importance. This is actual and reliable information for both the public and private sector.    
Locatieserver is a very powerfull geocoding service. Upon request it will return the position of an adress, street, place, neighbourhood, district, municipality, province, property boundary, highway number or hectometer marker.    
Soon Locatieserver will also support reverse geocoding. [Reverse geocoding is already available in bèta.](https://forum.pdok.nl/t/nieuw-reverse-geocoder-api-beschikbaar-om-te-testen-pdok-locatieserver/1544)    
Major advantage of Locatieserver compared to other geocoding services like Google and OpenStreetMap, is that it will also return the *official* adresses and names. Moreover it will return unique identifiers to link the search results to other sources of information within government. Also the data is updated frequently. For instance, adresses are updated daily.    
Although you have to register to acquire an API-key, using Locatieserver is free of charge. I'm not completely sure, but I don't think there is a maximum number of requests per day, like with the Google API. There is a fair use policy.    

So I think you can see why I am enthousiastic about Locatieserver ;-) However usage outside of the GIS community seems to be limited. So I would like to make a wrapper making it easier to use Locatieserver in R.     

## Do you want to know more?
Alas all documentation is in Dutch.
- [API Locatieserver](https://github.com/PDOK/locatieserver/wiki/API-Locatieserver)
- [Example requests](https://github.com/PDOK/locatieserver/wiki/Zoekvoorbeelden-Locatieserver)

## Would you like to participate?
Please contact me at w (dot) tadema (at) provinciegroningen (dot) nl
