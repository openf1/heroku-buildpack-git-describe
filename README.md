# heroku-buildpack-git-describe
Adds `APP_VERSION` env variable for Heroku apps.

## Usage
Simply run

```
$ heroku buildpacks:add https://github.com/openf1/heroku-buildpack-git-describe
```

to add it to your project. It should install on the next app deployment.
