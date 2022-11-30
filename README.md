## Binary relases of the Clarify JAVA application for Ewon devices.

Guide for usage can be found at: https://docs.clarify.io/developers/hardware/ewon-flexy

Example config:

```
username: your-clarify-integration-username
password: your-clarify-integration-password
fullpushtime:20
changepushtime:2
taggroups:ABCD
mqttlog:0
CAurl:https://letsencrypt.org/certs/isrgrootx1.pem
debug:0
```

Upload the Clarify.jar and the jvmrun file to `/usr/` on your device and reboot.

You will then find Clarify as an IO-Server in the management web interface for your device.
