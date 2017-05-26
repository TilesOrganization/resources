# Privacy Policy of Tiles

## BIND_DEVICE_ADMIN permission
### android:permission="android.permission.BIND_DEVICE_ADMIN"
Required to use the lock tile to lock the device using the Android Device Administration API

The lock tile, if activated, prompts the user to enable the device admin application if deactivated.
Once users enable the device admin application, the lock tile can be used to lock the device.
If users do not enable the device admin app, it remains on the device, but in an inactive state and the lock tile won't execute any action.
Prompt: To allow the tile to lock the device, please open settings and activate it as device administrator.
Description: Allow the lock tile to lock the device.
Device administrator activated state summary: Device administrator activated.
Device administrator activate state message: If activated, the lock tile will be allowed to lock the device.
Device administrator deactivated state summary: Device administrator deactivated.
Device administrator deactivate state message: If deactivated, the lock tile won't be allowed to lock the device.

Device Administration on Google Developers web site:
https://developer.android.com/guide/topics/admin/device-admin.html

Manifest.permission on Google Developers web site:
https://developer.android.com/reference/android/Manifest.permission.html#BIND_DEVICE_ADMIN
