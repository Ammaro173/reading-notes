# API Deployment

> [Back to Home](../README.md)

## How to install Heroku Command-Line on Ubuntu?

```bash
sudo curl https://cli-assets.heroku.com/install-ubuntu.sh | sh
```

## How to deploy a Static Website using Heroku CLI on Ubuntu?

heroku apps:create `<apps name>`

## create the container

heroku stack:set container

> then the regular ACP

git add .
git commit -m "good"
git push heroku main

## Conclusion

It is easy to install Heroku CLI and configure it on Ubuntu. We can deploy a static website on Heroku by creating a python app. Similarly, we can also host python, nodejs, php, ruby… applications.

> [Back to Home](../README.md)
