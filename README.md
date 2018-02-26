## mongo


show dbs
use <db>
show collections

```javascript
const port = process.env.PORT || 3000;
mongoose.connect(process.env.MONGO_URI+'/TodoApp' || 'mongodb://localhost:27017/TodoApp');
```

```JSON
  "scripts": {
    "start": "node server/server.js",
  },
 "engines": {
    "node": "8.9.1"
  }
```

```
$ git init
$ git remote add origin https://github.com/user/repo.git
$ git remote -v
$ git push -u origin master
```

```
$ heroku create
$ git remote -v
$ git push heroku master

```
$ heroku addons:create mongolab:sandbox -a mon-app-12345
$ heroku config -a mon-app-12345
```


```
$ git remote add heroku  https://git.heroku.com/mon-app-12345.git
$ git push heroku master
```

```
heroku config
heroku config:set JWT_SECRET=******
heroku config:get JWT_SECRET
heroku config:unset JWT_SECRET
```