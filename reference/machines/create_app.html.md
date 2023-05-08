```
curl -i -X POST \\
    -H "Authorization: Bearer ${FLY\_API\_TOKEN}" -H "Content-Type: application/json" \\
    "${FLY\_API\_PROTOCOL}://${FLY\_API\_HOSTNAME}/v1/apps" \\
  -d '{
      "app\_name": "user-functions",
      "org\_slug": "personal",
      "network": "user-functions-network"
    }'

```
**Status: 201**
