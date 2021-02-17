# Vue + Nginx running on Docker

### Run locally

```
npm install
npm run serve
```

### Run in Docker container

```
docker build -t vue .
docker run -it -p 80:80 --rm --name vue vue
```
