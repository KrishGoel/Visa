# Test authentication app
by **@KrishSkywalker7**
> Under construction

This is a test local authentication app based on JS with passport.JS, Express.JS and MongoDB

### npm commands and installations
```
npm init
npm install express --save
npm install passport
npm install body-parser --save
npm install passport-local --save
```

### MongoDB local machine setup
```
> cd C:\Program Files\MongoDB\Server\4.2\bin
> mongo
> use [datebaseName, myDatabase in this case]
> db.userInfo.insert({"username":"[NAME]", "password":"[PASSWORD]"})
> db.userInfo.find()
```
In index.js, please add the MongoDB link
