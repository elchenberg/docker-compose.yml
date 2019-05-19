# docker-compose.yml

## Variable substitution

```sh
echo -e "USERID=$(id -u)\nGROUPID=$(id -g)" | tee --append .env
```

<https://docs.docker.com/compose/compose-file/#variable-substitution>

## Extension fields

<https://docs.docker.com/compose/compose-file/#extension-fields>
