# Building

```bash
docker build -f Dockerfile.master -t tuxmonteiro/globodns.master .
docker build -f Dockerfile --build-arg GIT_URL=https://github.com/tuxmonteiro/GloboDNS.git --build-arg GIT_BRANCH=wip2 -t tuxmonteiro/globodns .
```
