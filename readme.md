# Beanstalkd container service

A basic [beanstalkd][https://kr.github.io/beanstalkd/] container.


## Configuration

There is nothing to configure. The service runs on the default port `11300` and is exposed for use.


## Docker Compose example

```
queue:
  image: c4tech/beanstalkd
  ports:
    - "11300:11300"
```
