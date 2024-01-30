# Backend
1. Install deps
`npm install`
2. create .env file
`cp env.example .env`
3. Generate ARN for app instance chime 
`aws chime-sdk-identity create-app-instance --name simple-chime-app`
4. start the server
`npm start`

# Frontend
`npm install`
`npm start`