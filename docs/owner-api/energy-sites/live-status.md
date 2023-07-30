# Live Status

## GET `api/1/energy_sites/{energy_site_id}/live_status`

Get the live status of the solar system.

### Response Body

```json
{
    "response": {
        "solar_power": 2290,
        "energy_left": 23076,
        "total_pack_energy": 26396,
        "percentage_charged": 87.4223367176845,
        "backup_capable": true,
        "battery_power": 0,
        "load_power": 712,
        "grid_status": "Active",
        "grid_services_active": false,
        "grid_power": -1578,
        "grid_services_power": 0,
        "generator_power": 0,
        "island_status": "on_grid",
        "storm_mode_active": false,
        "timestamp": "2023-07-30T10:39:30-06:00",
        "wall_connectors": []
    }
}
```
