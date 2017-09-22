# node-fusionchart-demo

Sample for creating FusionChart using Node and MongoDB

### Disclaimer ###
Created entirely by Mohamed Sanaulla. 

Fixed and uploaded to GitHub by Apidcloud for semantic-release [PR purposes](https://github.com/semantic-release/semantic-release/pull/431)

### How to get it running 
Based on the [original tutorial](http://www.fusioncharts.com/dev/using-with-server-side-languages/tutorials/creating-interactive-charts-using-node-express-and-mongodb.html#creating-rest-api-for-data-retrieval):
1. Install Node
2. Install MongoDB [accordingly](https://www.mongodb.org/downloads)
3. To now run a mongodb server, you will have to set a location to save its databases. You can do so by running, for instance, `$ mongod --dbpath=mongodb\data`
4. Populate a database by running `$ mongoimport -d fusion_demo -c fuel_price --type json --file data.json --jsonArray` - make sure to run this command inside the project folder, where data.json is located, or to change its path accordingly.
5. `$ npm start`
6. Open http://localhost:3300 in the browser
