# System Status

## GET `/api/system_status`

Get they system status of each powerwall.

### Response Body

```json
{
    "command_source": "Configuration",
    "battery_target_power": 0,
    "battery_target_reactive_power": 0,
    "nominal_full_pack_energy": 26407,
    "nominal_energy_remaining": 23408,
    "max_power_energy_remaining": 0,
    "max_power_energy_to_be_charged": 0,
    "max_charge_power": 10000,
    "max_discharge_power": 10000,
    "max_apparent_power": 10000,
    "instantaneous_max_discharge_power": 24000,
    "instantaneous_max_charge_power": 14000,
    "instantaneous_max_apparent_power": 11520,
    "hardware_capability_charge_power": 0,
    "hardware_capability_discharge_power": 0,
    "grid_services_power": -0,
    "system_island_state": "SystemGridConnected",
    "available_blocks": 2,
    "available_charger_blocks": 0,
    "battery_blocks": [
        {
            "Type": "",
            "PackagePartNumber": "6543210-05-B",
            "PackageSerialNumber": "TG12345678908S",
            "disabled_reasons": [],
            "pinv_state": "PINV_GridFollowing",
            "pinv_grid_state": "Grid_Compliant",
            "nominal_energy_remaining": 11678,
            "nominal_full_pack_energy": 13188,
            "p_out": 0,
            "q_out": 320,
            "v_out": 241.70000000000002,
            "f_out": 59.981,
            "i_out": -0.2,
            "energy_charged": 5857170,
            "energy_discharged": 5148630,
            "off_grid": false,
            "vf_mode": false,
            "wobble_detected": false,
            "charge_power_clamped": false,
            "backup_ready": true,
            "OpSeqState": "Active",
            "version": "30f95d0b4f5fae"
        }
    ],
    "ffr_power_availability_high": 11600,
    "ffr_power_availability_low": 5998,
    "load_charge_constraint": 0,
    "max_sustained_ramp_rate": 2500000,
    "grid_faults": [],
    "can_reboot": "Yes",
    "smart_inv_delta_p": 0,
    "smart_inv_delta_q": 0,
    "last_toggle_timestamp": "2023-07-30T02:05:07.370033-06:00",
    "solar_real_power_limit": 1.7976931348623157e+308,
    "score": 10000,
    "blocks_controlled": 2,
    "primary": true,
    "auxiliary_load": 0,
    "all_enable_lines_high": true,
    "inverter_nominal_usable_power": 11600,
    "expected_energy_remaining": 0
}
```

## GET `/api/system_status/grid_faults`

Not yet documented.

## GET `/api/system_status/grid_status`

Get current grid status.

### Response Body

```json

{
    "grid_status": "SystemGridConnected",
    "grid_services_active": false
}
```

## GET `/api/system_status/soe`

Get current powerwall battery percentage.

### Response Body

```json
{
    "percentage": 88.6019388064223
}
```
