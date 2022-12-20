# Seoul-Buger-Location-Analysis WebPage Using JavaScript
 To Run the Script, replace "ArcGIS Platform API Key", "SGIS service ID" and "SGIS Secret Key" to Your API Keys.
 
 1. Get Authentication Token from SGIS API using Fetch *getAuthToken()
 2. Get Census Data from SGIS API using Fetch *getData(AuthToken, year)
 3. Load Esri Map *esriMap(SGISData, popSum) and Web Feature Layer
 4. Add Spaital Anaysis Funcion 
 *createBuffer(locationGraphic, inputNumber), solveServiceArea(serviceAreaUrl,serviceAreaParams), showSpatialRelationship(string, value) ...
 5. Configure Popup *censusPopup(feature)
 6. Configure Chart using Chart.js *showCensusChart(popSum)
