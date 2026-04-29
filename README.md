# DockerPullerBuilder
Painless pull and build image using Github Actions
# Usage
Fork this repo and trigger your own Actions, load your artifact as follow:
```
unzip -p action_image_artifact_repo_latest.zip | docker load
```
# Note
If you are using build-to-registry workflow, please set the following secrets:
```
DOCKER_REGISTRY
DOCKER_USERNAME
DOCKER_PASSWORD
```
# Reference
[Dropdown for GitHub Workflows input parameters - Stack Overflow](https://stackoverflow.com/questions/69296314/dropdown-for-github-workflows-input-parameters)

[ishworkh/container-image-artifact-upload: Github action for uploading container image artifact](https://github.com/ishworkh/container-image-artifact-upload)

