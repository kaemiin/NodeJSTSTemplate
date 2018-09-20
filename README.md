# NodeJSTSTemplate

## Use Docker

```
docker run -it -v $(pwd):/workspace -v node_modules:/workspace/node_modules --name xxx kkarczmarczyk/node-yarn bash

docker exec -it xxx bash
```

## Compile TypeScript

```
tsc
```
