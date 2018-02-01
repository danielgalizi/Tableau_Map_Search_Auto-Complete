# Tableau Places Search Engine

## Why the Tableau Places Search Engine?
With the engine you can search, using Google's auto-complete feature, for places (addresses, stores, nature, etc) from all over the world and get the results into Tableau.
The Engine can interact and communicate with Tableau and you'll get the data into your viz, so, there is no need for coding, programming knowledge or complex structures. You'll only need Tableau Knowledge.


## Prerequisites
* You must have a published VIZ with parameters and a Google Places API Key
    - Get the Key for free here: (https://developers.google.com/places/web-service/get-api-key). 


## Setup
1. Create and configure your VIZ with the folowing parameters (You can use whatever parameter names you want) to receive:
    - LATITUDE;
    - LONGITUDE;
    - The text/address/place you searched for;
    - A flag returning number 1 if you activated the search.
    - If you are not using Tableau Public/Online, Don't worry! You just need to host the engine (Single HTML) in the same environment         you have your Tableau Server.
(You don't need to use all parameters.)
    
2. Publish your Viz and don't forget:
    -The URL of your published viz;
    -Parameter names(Tableau) you created inside your viz and;
    -Your Google places API Key.

3. Replace URL **VARIABLES** with the values you have from the previous step (don't forget to keep the separators):

<p><em>&nbsp; &nbsp; &nbsp; https://danielgalizi.github.io/Tableau_Places_Search/Tableau_Places_Search.html</em><strong>?</strong><br /><strong>&nbsp; &nbsp; &nbsp; par_name_actv</strong>=Activate parameter name<strong>&amp;</strong><br /><strong>&nbsp; &nbsp; &nbsp; par_name_lat</strong>=Latitude parameter name<strong>&amp;</strong><br /><strong>&nbsp; &nbsp; &nbsp; par_name_lon</strong>=Longitude parameter name<strong>&amp;</strong><br /><strong>&nbsp; &nbsp; &nbsp; par_name_return</strong>=(Returned text parameter name)<strong>&amp;</strong><br /><strong>&nbsp; &nbsp; &nbsp; google_api_key</strong>=Google API KEY<strong>&amp;</strong><br /><strong>&nbsp; &nbsp; &nbsp; viz_url</strong>=Your published viz link (copied from share button)</p>
  
Full URL:   

    https://danielgalizi.github.io/Tableau_Places_Search/Tableau_Places_Search.html?par_name_actv=ACTIVATE&par_name_lat=LAT_PAR&par_name_lon=LON_PAR&par_name_return=LOCATION_STR&google_api_key=AIzaSyCdit-GymHhJtNvB-kuXzN5rZKmsUqHRlU&viz_url=https://public.tableau.com/views/MAP_69/Painel1
[Click here to follow the full URL](https://danielgalizi.github.io/Tableau_Places_Search/Tableau_Places_Search.html?par_name_actv=ACTIVATE&par_name_lat=LAT_PAR&par_name_lon=LON_PAR&par_name_return=LOCATION_STR&google_api_key=AIzaSyCdit-GymHhJtNvB-kuXzN5rZKmsUqHRlU&viz_url=https://public.tableau.com/views/MAP_69/Painel1). 
 
 
## Usage
All you need to do is to type the desired place/address/street... (or part of it) in the text box and select the desired name in the auto-complete list. After clicking, the embedded viz parameters will receive the results.

## Contributions
Help is always appreciated.

## Documentation
[Visit the project website and read the documentation here.](https://github.com/danielgalizi/Tableau_Places_Search)

## Issues
Feel Free to fix and share any problems or bugs you encounter in the README or code.

## Authors

* **Daniel Galizi** - www.galizi.com

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
