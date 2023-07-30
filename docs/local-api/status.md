# Status

## GET `/api/status`

Get solar system status, includes VIN, start time, up time, software version.

### Response Body

```json
{
    "din": "1234567-00-E--TG123456789A4M",
    "start_time": "2023-07-27 00:09:48 +0800",
    "up_time_seconds": "73h59m25.955949683s",
    "is_new": false,
    "version": "23.12.10 30f95d0b",
    "git_hash": "098d905fecf529408886b84b5eefae94025f6466",
    "commission_count": 0,
    "device_type": "teg",
    "teg_type": "unknown",
    "sync_type": "v2.1",
    "leader": "",
    "followers": null,
    "cellular_disabled": false
}
```
