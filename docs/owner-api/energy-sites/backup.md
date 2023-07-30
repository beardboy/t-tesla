# Backup

## POST `api/1/energy_sites/{energy_site_id}/backup`

Set the battery backup reserve energy percentage for grid outages.

### Parameters

| Parameter              | Example | Description                        |
| :--------------------- | :------ | :--------------------------------- |
| backup_reserve_percent | 75      | The percentage for backup reserve. |

### Request Body

```json
{
    "backup_reserve_percent": 75
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
