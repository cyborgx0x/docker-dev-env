```
Get-Content .\Dockerfile-Node | docker build -t calssiq/eportal:node-env  -
docker push calssiq/eportal:node-env
```

```
Get-Content .\Dockerfile-Node | docker build -t calssiq/eportal:env-js-node18  -
docker push calssiq/eportal:env-js-node18
```