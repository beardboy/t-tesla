# Site Master

## GET `/api/sitemaster`

Get solar system site information.

### Response Body

```json
{
    "status": "StatusUp",
    "running": true,
    "connected_to_tesla": true,
    "power_supply_mode": false,
    "can_reboot": "Yes"
}
```

## POST `/api/sitemaster/stop`

Stop the solar system.

## GET `/api/sitemaster/run`

Start the solar system.

