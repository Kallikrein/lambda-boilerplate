lambda-boilerplate
===
usage
---

Installation  

Create a envAWS file at the root of the folder and put your amazon credentials there  
```
AWS_ACCESS_KEY_ID=...
AWS_SECRET_ACCESS_KEY=...
```

install upload dependencies  
```shell
npm install
```

install src dependencies  
```shell
cd src
npm install
```
node should be version 4.2.3 (lambda environment)

Build  

```shell
npm run zip
```

Deploy
```shell
npm run deploy
```

Build and deploy

```shell
npm start
```
