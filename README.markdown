# Testing go app on heroku

Using [heroku-buildpack-go](https://github.com/kr/heroku-buildpack-go).

```bash
heroku create --buildpack git://github.com/kr/heroku-buildpack-go.git
git push heroku master
```
