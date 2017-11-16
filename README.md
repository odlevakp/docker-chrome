# Chrome-unstable in Docker

A simple image containing an unstable, headless Google chrome browser inside
an Ubuntu 16.04 based image.


```sh
docker run -d \
-p 9222:9222 \
--name chrome \
--cap-add=SYS_ADMIN \
odlevakp/chrome:latest
```
