```
curl -i -X POST \\
    -H "Authorization: Bearer ${FLY\_API\_TOKEN}" -H "Content-Type: application/json" \\
    "https://${FLY\_API\_HOSTNAME}/v1/apps/user-functions/machines/d5683210c7968e/stop" 

```
**Status: 200**
```json
{
  "ok": true
}
```