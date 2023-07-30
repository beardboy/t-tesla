# Config

## GET `/api/config`

Get the vin of the powerwall gateway.

### Response Body

```json
{
    "vin": "1234567-00-E--TG123456789A4M"
}
```

## GET `/api/config/completed`

Get the current configuration of the powerwall gateway, including up time and software version.

### Response Body

```json
{
    "din": "1234567-00-E--TG123456789A4M",
    "start_time": "2023-07-27 00:09:48 +0800",
    "up_time_seconds": "72h57m46.637752645s",
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
