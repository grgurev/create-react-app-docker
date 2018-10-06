This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

#### Building and starting container
When starting container for first time don't forget to run `docker-compose run` command to install npm modules on host.
```
$ docker-compose build
$ docker-compose run --rm server npm install
$ docker-compose up
```
 #### For installing npm packages use
When container is running just execute npm install in container:
```
$ docker-compose exec app npm install <package-name>
```