# aiopsb2023-webserver


## Deployment

### Test on local PC

```sh
docker build -t webserver .
docker run -it --rm -p 8080:80 webserver 
```

### Deploy on server

```sh
git clone https://github.com/huidsp/aiopsb2023-webserver.git
cd aiopsb2023-webserver
docker build -t webserver .
docker run -d --rm -p 80:80 webserver 
```
