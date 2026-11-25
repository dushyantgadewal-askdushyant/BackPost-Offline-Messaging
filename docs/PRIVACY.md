# Privacy and nearby permissions

BackPost pairs nearby Android devices directly. It encrypts messages and file contents end to end in transit between paired devices. Compare pairing codes or verify fingerprints in person before trusting a device.

## What stays on your phone

BackPost stores your chat history, settings, and paired-device information locally. Your retention setting and the delete-chat action apply to your local chat history. The recipient controls their own copies. Files you save to shared Downloads can remain there after you delete a conversation. People who can open an unlocked phone may be able to see its conversations and files.

## What Android may request

| Access | Purpose |
| --- | --- |
| Nearby devices, Bluetooth, and Wi-Fi | Find another phone and create a direct connection. |
| Location permission on some Android versions | Enable nearby discovery when Android requires that permission. |
| Camera | Read another phone’s pairing QR. You can use Find nearby without the camera. |
| Notifications | Alert you to incoming activity and show when you have enabled temporary nearby availability. |
| File picker | Give BackPost access to a file you choose to send. |

BackPost uses Google Play services Nearby Connections to discover and connect to devices. Google documents that the Nearby SDK collects usage analytics, including information about discovery, connection performance, and the device. See [Google’s Nearby Connections overview](https://developers.google.com/nearby/connections/overview) for details.
