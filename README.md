## About

[NoVNC](https://novnc.com/info.html) is a HTML VNC client. This addon can handle multiples instances. 


## Installation

The installation of this add-on is pretty straightforward and not different in
comparison to installing any other Hass.io add-on.


![screenshot](images/screenshot.png)

## Configuration

Each parameters is mandatory (name, host, port). Add entry in settings array for earch vnc server. 

**Note**: _Remember to restart the add-on when the configuration is changed._

Example add-on configuration:

```json
{
  "settings": [
    {
      "name": "Hanbrake",
      "host": "192.168.0.143",
      "port": 5900
    },
    {
      "name": "JDownloader 2",
      "host": "192.168.0.143",
      "port": 5901
    }
  ]
}
```
