# Deploy Teleport
[Teleport](https://goteleport.com/) server

## Running binaries

```sh
docker exec -i container-id tctl/tsh
```

Replace: 
- `container-id` with container ID obtained from `docker ps`

## Authenticating nodes

Replace `REPLACE_WITH_TOKEN` in [node/config/teleport.yaml](https://github.com/DaSH-Lab-CSIS/deploy-teleport/blob/main/node/config/teleport.yaml) with a [join token](https://goteleport.com/docs/reference/join-methods/)
