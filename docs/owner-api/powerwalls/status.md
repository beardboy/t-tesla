# Status

## GET `api/1/powerwalls/{battery_id}/status`

Retrieve the current status of your powerwalls.

### Response Body

```json
{
    "response": {
        "site_name": "Wardenclyffe",
        "id": "1234567-00-E--TG123456789A5M",
        "energy_left": 23108.894736842107,
        "total_pack_energy": 26411,
        "percentage_charged": 87.49723500375642,
        "battery_power": 0
    }
}
```
