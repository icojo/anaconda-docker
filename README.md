# anaconda-docker
based on Evheniy Bystrov's evheniy/docker-data-science

```
docker pull icojo/anaconda-docker

docker run --name anaconda-docker -p 8888:8888 -v "$PWD/notebooks:/opt/notebooks" -d anaconda-docker bash

jupyter notebook --allow-root --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser
```
