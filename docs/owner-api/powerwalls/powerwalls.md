# Powerwall Data

## GET `api/1/powerwalls/{battery_id}`

Retrieve the current powerwall reading, components, site information, as well as Grid Outages.

### Response Body

```json
{
    "response": {
        "site_name": "Wardenclyffe",
        "energy_left": 0,
        "total_pack_energy": 1,
        "grid_status": "Active",
        "backup": {
            "backup_reserve_percent": 20,
            "events": [
                {
                    "timestamp": "2023-04-17T19:25:19-06:00",
                    "duration": 7469961
                },
                {
                    "timestamp": "2023-04-04T02:49:18-06:00",
                    "duration": 304975
                }            ],
            "events_count": 0,
            "total_events": 0
        },
        "user_settings": {
            "storm_mode_enabled": false,
            "powerwall_onboarding_settings_set": true,
            "powerwall_tesla_electric_interested_in": false,
            "sync_grid_alert_enabled": false,
            "breaker_alert_enabled": false
        },
        "components": {
            "solar": true,
            "solar_type": "solarglass",
            "battery": true,
            "grid": true,
            "backup": true,
            "gateway": "teg",
            "load_meter": true,
            "tou_capable": true,
            "storm_mode_capable": true,
            "flex_energy_request_capable": false,
            "car_charging_data_supported": false,
            "off_grid_vehicle_charging_reserve_supported": true,
            "vehicle_charging_performance_view_enabled": false,
            "vehicle_charging_solar_offset_view_enabled": false,
            "battery_solar_offset_view_enabled": true,
            "solar_value_enabled": true,
            "energy_value_header": "Energy Value",
            "energy_value_subheader": "Estimated Value",
            "show_grid_import_battery_source_cards": true,
            "backup_time_remaining_enabled": true,
            "battery_type": "ac_powerwall",
            "configurable": false,
            "grid_services_enabled": false
        },
        "installation_date": "2021-01-01T12:00:00-06:00",
        "power_reading": [
            {
                "timestamp": "2023-07-30T09:45:23-06:00",
                "load_power": 867,
                "solar_power": 3730,
                "grid_power": -2863,
                "battery_power": 0,
                "generator_power": 0
            }
        ],
        "battery_count": 0
    }
}
```
