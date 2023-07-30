# Powerwalls

## GET `/api/powerwalls`

Detailed powerwall and gateway configuration, diagonostics, firmware, and update status.

### Response Body

```json
{
    "enumerating": false,
    "updating": false,
    "checking_if_offgrid": false,
    "running_phase_detection": false,
    "phase_detection_last_error": "no phase information",
    "bubble_shedding": false,
    "on_grid_check_error": "run sitemanager flag enabled, sitemanager process is running",
    "grid_qualifying": false,
    "grid_code_validating": false,
    "phase_detection_not_available": true,
    "powerwalls": [
        {
            "Type": "",
            "PackagePartNumber": "1234567-05-B",
            "PackageSerialNumber": "TG123456789V61",
            "type": "ACPW",
            "grid_state": "Grid_Uncompliant",
            "grid_reconnection_time_seconds": 0,
            "under_phase_detection": false,
            "updating": false,
            "commissioning_diagnostic": {
                "name": "Commissioning",
                "category": "InternalComms",
                "disruptive": false,
                "inputs": null,
                "checks": [
                    {
                        "name": "CAN connectivity",
                        "status": "fail",
                        "start_time": "2023-07-30T01:48:19.355910442-06:00",
                        "end_time": "2023-07-30T01:48:19.355915942-06:00",
                        "message": "Cannot perform this action with site controller running. From landing page, either \"STOP SYSTEM\" or \"RUN WIZARD\" to proceed.",
                        "results": {},
                        "debug": {},
                        "checks": null
                    },
                    {
                        "name": "Enable switch",
                        "status": "fail",
                        "start_time": "2023-07-30T01:48:19.355920442-06:00",
                        "end_time": "2023-07-30T01:48:19.355924817-06:00",
                        "message": "Cannot perform this action with site controller running. From landing page, either \"STOP SYSTEM\" or \"RUN WIZARD\" to proceed.",
                        "results": {},
                        "debug": {},
                        "checks": null
                    },
                    {
                        "name": "Internal communications",
                        "status": "fail",
                        "start_time": "2023-07-30T01:48:19.355929066-06:00",
                        "end_time": "2023-07-30T01:48:19.355933316-06:00",
                        "message": "Cannot perform this action with site controller running. From landing page, either \"STOP SYSTEM\" or \"RUN WIZARD\" to proceed.",
                        "results": {},
                        "debug": {},
                        "checks": null
                    },
                    {
                        "name": "Firmware up-to-date",
                        "status": "fail",
                        "start_time": "2023-07-30T01:48:19.355937441-06:00",
                        "end_time": "2023-07-30T01:48:19.355941691-06:00",
                        "message": "Cannot perform this action with site controller running. From landing page, either \"STOP SYSTEM\" or \"RUN WIZARD\" to proceed.",
                        "results": {},
                        "debug": {},
                        "checks": null
                    }
                ],
                "alert": false
            },
            "update_diagnostic": {
                "name": "Firmware Update",
                "category": "InternalComms",
                "disruptive": true,
                "inputs": null,
                "checks": [
                    {
                        "name": "Powerwall firmware",
                        "status": "not_run",
                        "start_time": null,
                        "end_time": null,
                        "progress": 0,
                        "results": null,
                        "debug": null,
                        "checks": null
                    },
                    {
                        "name": "Battery firmware",
                        "status": "not_run",
                        "start_time": null,
                        "end_time": null,
                        "progress": 0,
                        "results": null,
                        "debug": null,
                        "checks": null
                    },
                    {
                        "name": "Inverter firmware",
                        "status": "not_run",
                        "start_time": null,
                        "end_time": null,
                        "progress": 0,
                        "results": null,
                        "debug": null,
                        "checks": null
                    },
                    {
                        "name": "Grid code",
                        "status": "not_run",
                        "start_time": null,
                        "end_time": null,
                        "progress": 0,
                        "results": null,
                        "debug": null,
                        "checks": null
                    }
                ],
                "alert": false
            },
            "bc_type": null,
            "in_config": true
        }
    ],
    "gateway_din": "1234567-00-E--TG123456789A4M",
    "sync": {
        "updating": false,
        "commissioning_diagnostic": {
            "name": "Commissioning",
            "category": "InternalComms",
            "disruptive": false,
            "inputs": null,
            "checks": [
                {
                    "name": "CAN connectivity",
                    "status": "fail",
                    "start_time": "2023-07-30T01:48:19.356202928-06:00",
                    "end_time": "2023-07-30T01:48:19.356208303-06:00",
                    "message": "Cannot perform this action with site controller running. From landing page, either \"STOP SYSTEM\" or \"RUN WIZARD\" to proceed.",
                    "results": {},
                    "debug": {},
                    "checks": null
                },
                {
                    "name": "Firmware up-to-date",
                    "status": "fail",
                    "start_time": "2023-07-30T01:48:19.356212928-06:00",
                    "end_time": "2023-07-30T01:48:19.356217052-06:00",
                    "message": "Cannot perform this action with site controller running. From landing page, either \"STOP SYSTEM\" or \"RUN WIZARD\" to proceed.",
                    "results": {},
                    "debug": {},
                    "checks": null
                }
            ],
            "alert": false
        },
        "update_diagnostic": {
            "name": "Firmware Update",
            "category": "InternalComms",
            "disruptive": true,
            "inputs": null,
            "checks": [
                {
                    "name": "Synchronizer firmware",
                    "status": "not_run",
                    "start_time": null,
                    "end_time": null,
                    "progress": 0,
                    "results": null,
                    "debug": null,
                    "checks": null
                },
                {
                    "name": "Islanding configuration",
                    "status": "not_run",
                    "start_time": null,
                    "end_time": null,
                    "progress": 0,
                    "results": null,
                    "debug": null,
                    "checks": null
                },
                {
                    "name": "Grid code",
                    "status": "not_run",
                    "start_time": null,
                    "end_time": null,
                    "progress": 0,
                    "results": null,
                    "debug": null,
                    "checks": null
                }
            ],
            "alert": false
        }
    },
    "msa": null,
    "states": null
}
```

## GET `/api/powerwalls/status`

Current powerwall status.

### Response Body

```json
{
    "enumerating": false,
    "updating": false,
    "checking_if_offgrid": false,
    "running_phase_detection": false,
    "phase_detection_last_error": "no phase information",
    "bubble_shedding": false,
    "on_grid_check_error": "run sitemanager flag enabled, sitemanager process is running",
    "grid_qualifying": false,
    "grid_code_validating": false,
    "phase_detection_not_available": true
}
```