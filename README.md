# Install [Node](https://nodejs.org/en/download)

**Run commands one by one in CMD:**

1. `npm config set legacy-peer-deps true`
2. `npm install ajv@latest ajv-keywords@latest`
3. `npm install --save-dev @babel/plugin-proposal-private-property-in-object`

**Now create a folder in a specific drive, and then in that folder run the following commands:**

1. `npx create-react-app my-app`
2. `cd my-app`
3. `npm start` (to run the app on the server)
4. `npx kill-port 3000` (3000 is the port number for stopping the app)
