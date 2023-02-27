# MyUplink integration for Home Assistant
Custom Home Assistant integration for devices and sensors in [myUplink](https://myuplink.com/) account.

This integration should work with most smart devices from brands listed [here](https://myuplink.com/legal/works-with/en).

![example view](example-device-view.png)

## Install
### HACS
The easiest way to install this component is by clicking the badge below, which adds this repo as a custom repo in your HASS instance.

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?category=Integration&owner=jaroschek&repository=home-assistant-myuplink)

You can also add the integration manually by copying `custom_components/myuplink` into `<HASS config directory>/custom_components`
### Configuration

To use this integration, you need to make an application at [dev.myuplink.com](https://dev.myuplink.com/).  
Remember to set a valid Callback Url. It might be the easiest to use `https://my.home-assistant.io/redirect/oauth`.
_Note: You cannot edit the Callback Url after the application has been created, even though the GUI makes you think so. Create a new one if you want to change it._

Start the myUplink integration setup and copy the Client Identifier and Client Secret from your myUplink-application into the OAuth text fields.

Next, approve access via the OAuth pop-up and you should be good to go!