# example-dockerize-webdriverio

This is a simple example of WebdriverIO and Selenium Chrome dockerized.  The below instructions will create a docker image for WebdriverIO and then create a docker container for it along with creating a docker container for for selenium/standalone-chrome from a downloaded image.  It will then spin up the containers and run a simple test against the WebdriverIO website.

## Getting Started

After cloning the repository, navigate to example-dockerize-webdriverio/webdriverio-test:

```
cd example-dockerize-webdriverio/webdriverio-test
```

Run docker compose:
```
docker-compose up --build
```