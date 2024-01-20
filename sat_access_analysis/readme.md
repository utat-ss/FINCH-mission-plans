This simulation uses the Cesium3D data set for all the buildings. To run it, you'll need to create your own private 
token on the Cesium database. To create a tokemn:

1. Create an account on the cesium ion website,
https://cesium.com/platform/cesium-ion/ 
2. Log in and create an access token named STK. Include the following scopes:
    - assets:ist
    - assets:read
    - geocode
3. Open STK and in Edt open preferences
    - Click on Data Services
    - double click on Cesium Ion 
    - click the plus button under "access tokens" then give it a name and paste your token
4. Open the scenario properties > Basic > 3D tiles
5. Click on Hosted > Cesium
6. Under global manager, click add 3D Tilesets and add Cesium OSM buildings
7. Check that you can see buildings in the 3D view

This video was used as reference
https://www.youtube.com/watch?v=YuxJMom_T9M 
