# Geo Analysis

### Get backend config
Get backend config from div (id="optionConfigProperties")
### Get frontend config
Get frontend config from file('/doc/api/config/componentSetting.json')
### API call
* **Get mode data**

    _`/rest/mode-service/mode/load`_
* **Get polygon list data**

    _`/rest/polygon-service/polygon/list`_
* **Get permission setting**

    _`/rest/systemmanagement-service/userGroup/permission/Geo-Analysis`_

### WebSocket
Connect data-summary webSocket: listening to server side, update available timeSetting (date/hour) when needed.