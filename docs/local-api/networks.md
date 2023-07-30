# Networks

## GET `/api/networks`

Get the network configuration of the solar system. Includes LAN, Cellular, and WiFi.

### Response Body

```json
[
    {
        "network_name": "ethernet_tesla_internal_default",
        "interface": "EthType",
        "enabled": true,
        "dhcp": true,
        "extra_ips": [
            {
                "ip": "192.168.90.2",
                "netmask": 24
            }
        ],
        "active": false,
        "primary": false,
        "lastTeslaConnected": false,
        "lastInternetConnected": false
    },
    {
        "network_name": "gsm_tesla_internal_default",
        "interface": "GsmType",
        "enabled": true,
        "dhcp": null,
        "active": true,
        "primary": false,
        "lastTeslaConnected": false,
        "lastInternetConnected": false,
        "iface_network_info": {
            "network_name": "gsm_tesla_internal_default",
            "ip_networks": [
                {
                    "IP": "1.2.3.4",
                    "Mask": "/////w=="
                }
            ],
            "gateway": "1.2.3.4",
            "interface": "GsmType",
            "state": "DeviceStateReady",
            "state_reason": "DeviceStateReasonNone",
            "signal_strength": 100,
            "hw_address": ""
        }
    },
    {
        "network_name": "TeslaWifi",
        "interface": "WifiType",
        "enabled": true,
        "dhcp": true,
        "security_type": "WPA3_Personal",
        "username": "",
        "active": true,
        "primary": true,
        "lastTeslaConnected": true,
        "lastInternetConnected": true,
        "iface_network_info": {
            "network_name": "TeslaWifi",
            "ip_networks": [
                {
                    "IP": "1.2.3.4",
                    "Mask": "////AA=="
                }
            ],
            "gateway": "1.2.3.1",
            "interface": "WifiType",
            "state": "DeviceStateReady",
            "state_reason": "DeviceStateReasonNone",
            "signal_strength": 58,
            "hw_address": "AB:12:34:A1:B2:C3"
        }
    }
]
```
