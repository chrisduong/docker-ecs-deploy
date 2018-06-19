# ECS deployment with Docker

**Copied Python code from:** [https://bitbucket.org/awslabs/amazon-ecs-bitbucket-pipelines-python/](https://bitbucket.org/awslabs/amazon-ecs-bitbucket-pipelines-python/)

**Dockerfile from:** [https://hub.docker.com/r/jpbarto/boto3/~/dockerfile/](https://hub.docker.com/r/jpbarto/boto3/~/dockerfile/)

## Deploy

export ECS_CLUSTER_NAME=
export ECS_SERVICE_NAME=
export ECS_TASK_FAMILY_NAME=

```sh
docker run <> task_definition.json \
  <your_image>  \
  2 \
  100 \
  200
```
