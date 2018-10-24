# Docker-based notebook
## Run from a ready docker image
```sh
docker run -it -p 8888:8888 -v $PWD:/notebooks arthursjiang/ai_learn
open http://localhost:8888
```
## Build a customized docker image
```sh
cd pytorch
# custorize the Dockerfile and rebuild
bash build.sh
# run notebook
bash container_run.sh
```

