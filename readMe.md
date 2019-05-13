## Restaurant Search Engine

We developed a search engine for restaurants using the Zomato restaurants dataset at Kaggle. Handled large datasets using MongoDB and deployed the data onto mLab cloud. In this application, the user can make multiple search requests and filter his search by choosing one of the filter types such as country, nearby restaurants, Cuisine types, etc. Also implemented geospatial queries to show the nearby restaurants and integrating with googleMaps API to show the location of the restaurant.  Tech Stack: <MongoDB (mLab), NodeJS, HTML, JavaScript/>

### Requirements

- Install Node on your system using the following command for MacOS:
```
brew install node
```
- Type in the following command in Terminal to check the Node and NPM version
```
node -v
npm -v
```

- Set Url in the server.js file as follows:

#### To connect to the mLab cloud database service:
```
mongodb://ks4049:project123@ds227332.mlab.com:27332/project"
mongodb://ks4049:project123@ds157493.mlab.com:57493/gridfs"
```
OR
#### To connect to the local mongo data:
```
mongodb://localhost:27017/project
mongodb://localhost:27017/gridfs
```
	
### Steps to run:
Clone the repository and change directory to the cloned repository.
```
git clone https://github.com/ks4049/Restaurants-Search-Engine.git
cd Restaurants-Search-Engine
```
Install the dependencies required for the application.
```
npm install
```
The above command installs all the dependencies required for the application.

#### Command to run the server:
```
node server.js
```

#### Command to run the application:
```
localhost:3000
```

