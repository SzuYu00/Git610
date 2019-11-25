# Git610

Setting Up:
This web page is constructed upon the basic framework provided by the Reactjs.org tutorial.
Required setups starts with:
 1. Download Node.js from https://nodejs.org/en/download/
 2. Running commands (for MacOS): 
      npx create-react-app my-app
      cd my-app
      npm install
      npm start
    From the terminal
 
The directories are a little redundant in the repository but everything essential should be included within the my-app directory. However, for some reason Guthub has the "node_modules" directory added to the gitignore list. Therefore it is necessary to execute command "npm install" once within the folder where all the src directory and public directory exist.  

Feature Notes:
News feed is set to request every 5 seconds, and set to only render the top 3 articles instead of the full 10 headlines. However the google news API doesn't seem to have such frequent headline updates, therefore it does not get new feed every 5 seconds. The requests however, can still be seen within the network activity.
The actually API key for News feed within file "src/components/newsAPI/newsAPI.js" has been replaced by API_KEY, replace it with an active key to obtain functionality (will be provided within submission text).
