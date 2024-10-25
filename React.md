# How to create react app  and host it?

### Step 1: Install Node.js

  Url ->  https://node.js.org/en
  
  download and istall node.js
  ```
  node--v
  ````

  ### Step 2: Install create react app
1.   Open terminal/go to directory 
       ```
        npm  install -g create-react-app
        ```
        ```
        npx  create-react-app my-app
        ```

  ### Step 3: Navigate into your project name
        cd my-app
      

  #### Start development server to set up
    
      npm run start
    
  ### Step 4: Build the Project for Production
    npm run build




 # Step 5: Hosting in Github pages
  Google ``create react app`` follow the steps

  
### Step 1: Add homepage to package.json
    "homepage": "https://myusername.github.io/my-app",

Step 2: Install gh-pages and add deploy to scripts in package.json

    npm install --save gh-pages
    
Add the following scripts in your package.json:


      "predeploy": "npm run build",
       "deploy": "gh-pages -d build",

### Step 3: Deploy the site by running npm run deploy 
  
         npm run deploy
  



