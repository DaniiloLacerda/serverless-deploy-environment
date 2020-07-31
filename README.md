# Serverless deploy environment
This project, get message in See [WhatTheCommit.com](http://whatthecommit.com/) and insert in dynamo database.

Do deploy in different environments

### Installation serverless
    npm install -g serverless
    
### Installation
    npm i

### Deploy
```sh
sls deploy
```

### Deploy prod enviroment
```sh
sls deploy --stage prod
```

### Invoke local 
    npm run invokeLocal
    
### Invoke aws 
    npm run invoke
    
### Invoke local  prod environment
    npm run invokeLocalProd
    
### Invoke aws prod environment
    npm run invokeProd

