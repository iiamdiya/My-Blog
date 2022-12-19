

Introducing My Personal Daily Blog Application Built with React

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.


### After you run the application by "npm run start"

## Type "npx json-server --watch ./data/db.json --port 8000" 

npx is a tool that comes with npm (Node Package Manager) that allows you to run npm packages, including command-line tools.

The json-server package is a utility that creates a simple server that serves a JSON file as a REST API. It can be used for development or testing purposes, or as a mock API for front-end development.

The --watch flag tells json-server to watch the specified file (./data/db.json in this case) for changes and automatically update the API endpoints when the file changes.

The --port flag specifies the port on which the server should listen for requests. In this case, the server will listen on port 8000.

So, the command will start a json-server instance that serves the API endpoints defined in the ./data/db.json file, listens for changes to that file, and listens for requests on port 8000.

### Then you are ready to use this application

![image](https://user-images.githubusercontent.com/71397300/208496863-f33a5419-aa94-4407-9070-54fc50c2c228.png)
