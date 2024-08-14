# docker-sync

This repo contains a list of images that are synced from DockerHub to ghcr.io.

Generally, you should not use this repo for syncing images. You should:

1. Seek out alternative sources for official images
2. Understand whether it needs syncing at all - Some images are unlimited through our Docker Sponsored Open Source and Docker Verified Publisher programs.

This is the last resort and may suffer from missing image tags and may stop working altogether.

## Usage

If you absolutely can't find the image elsewhere, add the repository to the array in the `.github/workflows/docker-sync.yaml` file.
No tags, no `docker.io`, just `org/repo`.

