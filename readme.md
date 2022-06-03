# Node.js Blockchain Application


### Getting Started

Install the dependencies
```sh
npm install
```
### Running all test cases

```sh
npm run test
```

### Running the application

```sh
# Starting first peer
npm run dev

# Starting second peer
HTTP_PORT=3002 P2P_PORT=5002 PEERS=ws://localhost:5001 npm run dev

# Starting third peer
HTTP_PORT=3003 P2P_PORT=5003 PEERS=ws://localhost:5001,ws://localhost:5002 npm run dev
```

### Running the app using docker-compose

```sh
docker-compose -f docker-compose.yml up -d
```
