# Node Express App (Node.js)
Express app

## Build & run server

```
cd node-express-app
cp .env.sample .env
# Adjust the settings in the `.env` file manually if needed
make restart
```

## Sending CURL requests to REST API

On your local development environment (make sure that you're running this command from a host that can resolve
`localhost` name to a correct IP address, and that TCP port 8177 is reachable on the target machine):

```
curl http://localhost:8177/api/v1/
```