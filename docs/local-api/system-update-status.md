# System Update Status

## GET `/api/system/update/status`

Get they system update status.

### Response Body

```json
{
    "state": "/update_succeeded",
    "info": {
        "status": [
            "nonactionable"
        ]
    },
    "current_time": 1690706953182,
    "last_status_time": 1690704590334,
    "version": "23.12.10 30f95d0b",
    "offline_updating": false,
    "offline_update_error": "",
    "estimated_bytes_per_second": null
}
```