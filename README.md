To start, first, clone the repository, then run the following commands:

```
docker build -t foodholics .
docker run --name foodholics -d -p 3000:3000 foodholics
```