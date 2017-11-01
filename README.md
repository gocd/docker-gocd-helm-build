# Docker GoCD Helm Build
Docker image for running GoCD Helm Chart Tests.

This image contains:
* [jq](https://stedolan.github.io/jq/)
* [curl](https://curl.haxx.se/)
* [bash](https://www.gnu.org/software/bash/)

# Docker Image
You could either download the latest built image from docker hub or build one locally with the dockerfile.

## 1.1 Download the Image

```
docker pull gocddev/gocd-helm-build:v0.1.0
```

## 1.2 Build One Locally

```
docker build -t <TAG_NAME> .
```

# Usage
Start the container with this:

```
docker run -it gocddev/gocd-helm-build:v0.1.0 /bin/bash
```

# License

```
Copyright 2017 ThoughtWorks, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
