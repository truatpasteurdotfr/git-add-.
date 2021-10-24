# singularity-docker-stream8-chrome
Google Chrome container based on a CentOS Stream 8 x86_64 docker image  built from github actions

(toy) singularity image produced by github actions available at `ghcr.io/truatpasteurdotfr/singularity-docker-stream8-chrome:latest`

Tru <tru@pasteur.fr>

## Why?
- workaround solution when a Chrome release is not running on CentOS-7 because the required glibc is not satisfied
(yes, I know... CentOS-7 is not on the list of approved OS).

## Caveat
- playground, use at your own risk!

## Running without installation:
```
singularity run  -B /run oras://ghcr.io/truatpasteurdotfr/singularity-docker-stream8-chrome:latest
```
## Building:
```
sudo singularity build singularity-docker-stream8-chrome.sif  Singularity
```

