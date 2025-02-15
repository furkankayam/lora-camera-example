## 🛜 LoRa Camera Example

#### WIFI and MQTT

```ino
const char* WiFi_SSID = "<WIFI_USERNAME>";
const char* WiFi_PASS = "<WIFI_PASSWORD>";
const char* MQTT_SERVER = "<MQTT_SERVER>";
const char* MQTT_CLIENT_ID = "route";
const char* MQTT_SUB_TOPIC = "route_subscribe";
```

#### MQTT Publish JSON

```json
{
  "route": [
    { "1": "r" },
    { "2": "l" },
    { "3": "s" }
  ]
}
```

#### LoRa Slave OUTPUT

```txt
1:r|2:l|3:s
```
