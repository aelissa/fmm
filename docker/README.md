A docker image to run fmm through jupyter lab. It builds the latest Ubuntu distribution and includes Python2 and Python3 kernels. 

### Build the docker image

Under the project folder of fmm, run the following command to build the image

```shell
docker build -f docker/dockerfile . -t fmm:0.1.0
```
### Run the image

```shell
docker run -p 8888:8888 fmm:0.1.0
```

