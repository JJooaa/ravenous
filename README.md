# Yelp clone || Ravenous

In this project I've used the yelp api to fetch data, save it and display it. 
You can search for restaurants in the "Search Businesses" input field. 
The "Where?" input field allows you to specify an area of which the restaurants will be shown.
Also 3 categories for "Best Match", "Highest Rated" and "Most Reviewed". 

## Installation 

```bash
git clone https://github.com/JJooaa/ravenous
```

After cloning run;

```bash
npm install
```

If you want to run it locally in the development mode use the command;
```bash
npm start
```

## Api key for development

In order to get your own api key, you need to have a yelp account.
If you want to fetch data in a development mode you need to create an .env file in the root directory of the project.
Inside the .env file you want to add an environment-specific variable. 
For example; REACT_APP_API_KEY=123123123
Now you're good to go.


Created Using the Create-React-App.