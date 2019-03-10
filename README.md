# OpenHAB-Smartthings

This is an openHAB binding for use with the Samsung Smartthings hub. On 3/5/19 it was submitted to openHAB for review and addition to openHAB bindings collection. Until it has been accepted and added to the openHAB platform you can install it from here.

## Requires Smartthings Classic App

This binding only works with the **Smartthings Classic** app for your phone.

## Installation instructions

1. The org.openhab.binding.smartthings-2.5.0-SNAPSHOT.jar file which is located at org.openhab.binding.smartthings/target has to be copied to the addons folder in your openHAB installation.  If you are using Openhabian this will be in the Samba share: openHAB/addons. 
2. If openHAB is currently running it will need to be restarted (On Linux: sudo /etc/init.d/openhab2 stop followed by sudo /etc/init.d/openhab2 start).
3. Then follow the setup instructions in the README.md file in the org.openhab.binding.smartthing directory. Make sure to perform the **Smartthings Configuration** steps described in that file.

## How to report issues

If you discover one of your devices doesn't work as expected please follow the instructions in the [Troubleshooting file](org.openhab.binding.smartthings/Troubleshooting.md) and raise an issue on my Github Repo [BobRak](https://github.com/BobRak/)
