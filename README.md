# seismicloud-image
public docker image for seismicloud

### Run with Docker
```
docker pull ghcr.io/denolle-lab/seismicloud-image:latest
docker run -it --rm ghcr.io/denolle-lab/seismicloud-image:latest python --version
```
Note: you can also pull specific versions tagged by github SHA (ghcr.io/denolle-lab/seismicloud-image:861dbed)

### Build Docker image:
Note: this currently happens automatically with GitHub Actions with every commit to the 'main' branch
```
docker buildx build . -t seismicloud:latest
```
