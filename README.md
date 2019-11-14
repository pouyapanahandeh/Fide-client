# fide-client


## Branching Methodology
> Master Branch: Master Branch remain un changed till code base become stable.
> Codes will push to the Dev Branches and when it becomes stable it will merge to the MVP branch.
> MVP branch is include the latest version of MVP and when it become stable it would merge to Master/Origin.

## Fide API Documentation

For sending request and checking the Application API you need to use post man.

### Get Method, to get the latest Location. ###

```
api.fidebot.online/location
// Value for passing through the API is:
// 1 - Latitude
// 2 - Longitude
```
### Get Method, to get the status of the ride ###

```
api.fidebot.online/ridestatus
// Pass one boolean value.
// 1 - isItEnd
```

### Get Method, to get the Service status ###
```
api.fidebot.online/serviceStatus
// 1 - location
// 2 - isItEnd
```

### Get Method,

### 
###


## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
