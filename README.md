## Docker Learning with simple application 

### To build a simple nodejs application , start with init
```
npm init
```


### Check the node app on local server.
```
node index.js
```


#### Build a docker container and run it
```
docker build -t xiashay/hey-node:0.0.1.RELEASE .
```

### Check the running container file
```
docker container ls
```

### Push the container onto docker hub
```
docker push xiakshay/hey-node:0.0.1.RELEASE
```


