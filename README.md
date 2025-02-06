# 2025-02-06-docker

```bash
docker run \
  --rm \
  -it \
  -e PASSWORD="password" \
  -p 8787:8787 \
  -v /$(pwd):/home/rstudio/pizza \
  rocker/rstudio:4.4.2
```
