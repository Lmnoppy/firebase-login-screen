# Firebase-auth
Basic user auth login with email and password built with React ui powered by Google firebase

Built following the tutorials from:

Webdev simplified: 
https://www.youtube.com/watch?v=PKwu15ldZ7k&t=2731s 

Remotestack:
https://www.remotestack.io/react-bootstrap-login-register-ui-templates/ 

Theme colours from:
https://mycolor.space/?hex=%23845EC2&sub=1 

## Requires 

```
  "dependencies": {
    "bootstrap": "^4.5.2",
    "firebase": "^8.6.8",
    "react": "^16.13.1",
    "react-bootstrap": "^1.6.1",
    "react-dom": "^16.13.1",
    "react-router-dom": "^5.2.0",
    "react-scripts": "3.1.2"
  },
```

Create a local file called .env and add your firebase config, this will allow local development. 
```
REACT_APP_FIREBASE_API_KEY=
REACT_APP_FIREBASE_AUTH_DOMAIN=
REACT_APP_FIREBASE_DATABASE_URL=
REACT_APP_FIREBASE_PROJECT_ID=
REACT_APP_FIREBASE_STORAGE_BUCKET=
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=
REACT_APP_FIREBASE_APP_ID=
```

## Guides

### Helpful commands 

#### Npm
```
npm run-script build
npm start
```

#### Firebase

Install

```
npm install --save firebase
npm install -g firebase-tools
```

Setup
```
firebase init
```

Run locally
```
firebase serve
```

Deploy
```
firebase deploy
```
