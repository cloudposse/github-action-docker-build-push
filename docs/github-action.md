<!-- markdownlint-disable -->
## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| build-args | List of build-time variables | N/A | false |
| file | Dockerfile name | Dockerfile | false |
| login | Docker login |  | false |
| organization | Organization | N/A | true |
| password | Docker password |  | false |
| registry | Docker registry | N/A | true |
| repository | Repository | N/A | true |
| tags | List of tags (supports https://github.com/docker/metadata-action#tags-input) | N/A | false |
| workdir | Working directory | ./ | false |

## Outputs

| Name | Description |
|------|-------------|
| image | Docker image name |
| tag | Docker image tag |
<!-- markdownlint-restore -->
