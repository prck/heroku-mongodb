## mongo


show dbs
use <db>
show collections

```` js
const port = process.env.PORT || 3000;
mongoose.connect(process.env.MONGO_URI || 'mongodb://localhost:27017/TodoApp');
````

```` JSON
  "scripts": {
    "start": "node server/server.js",
  },
 "engines": {
    "node": "8.9.1"
  }
````

```` console
heroku addons:create mongolab:sandbox -a mon-app-12345
heroku config -a mon-app-12345
````

```` console
git init
git remote add origin https://github.com/user/repo.git
git remote -v
git push -u origin master
````