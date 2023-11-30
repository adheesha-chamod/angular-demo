# Angular Demo

## Prerequisite
Used tools and technologies:
* Angular CLI: 16.0.0
* Node: 20.10.0
* npm (Package Manager): 10.2.3

## Run

Open the terminal from the project location and, run the below commands.

#### 1. Install all the dependencies
```
npm install --legacy-peer-deps
```

#### 2. Start the json-server
Do this in another terminal that opened from the project location.
```
npx json-server --watch db.json
```

#### 3. Start the Angular application
```
ng serve
```