# Site Name

## POST `api/1/energy_sites/{energy_site_id}/site_name`

Set your energy site name.

### Parameters

| Parameter | Example      | Description           |
| :-------- | :----------- | :-------------------- |
| site_name | Wardenclyffe | New energy site name. |

### Request Body

```json
{
    "site_name": "Wardenclyffe"
}
```
### Response Body

```json
{
  "response": {
    "code": 201,
    "message": "Updated"
  }
}
```
