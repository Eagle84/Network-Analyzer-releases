# Privacy Policy — Network 3D Live

_Last updated: 2026-11-14_

Network 3D Live ("the app", Google Play package `com.eagleslab.wirelessscanner`) is a local
network scanner and analyzer. This policy explains what the app accesses, what it stores, and
what leaves your device.

## Summary

- The app works on your own device and your own local network. **We do not run a server, we do
  not have user accounts, and we do not receive any data from the app.**
- There is no advertising, no analytics and no crash-reporting service in the app.
- The device list, names and router login you give the app are stored **only on your device**.
- The only connection to a service outside your local network is Google Play's update check
  (see "Google Play" below).

## What the app reads and stores on your device

- **Wi‑Fi and network information**: the network name (SSID), your device's IP address, the
  gateway, DNS and subnet. Used to show your network and to scan it.
- **Devices on your local network**: IP address, MAC address, hostname, hardware vendor,
  and, where a device announces it, a friendly name. These are found by scanning the network
  you are connected to (ping and port probes, mDNS/DNS‑SD and NetBIOS name queries) and are
  shown to you.
- **Your own labels**: names you give devices and whether you mark them trusted.
- **Presence history**: when each device was seen, kept for up to 30 days, used for the
  activity charts and for telling you when a new device appears.
- **Schedules** you create for blocking or limiting a device (rooted phones only).
- **Router details** (optional): if you connect your router, the names and MAC addresses
  from your router's own device list.

All of this is stored in the app's private storage. Android backup is turned off for the app,
so it is not copied to cloud backups.

## Router sign‑in (optional)

If you enter your router's admin login, the app stores it **encrypted on your device** using an
Android Keystore key. It is tied to the Wi‑Fi network you saved it on and is only used to sign
in to that router's admin page on your local network, to read its device list and, if you ask,
to block a device on it. It is never sent to us or to any other service. You can remove it at
any time with "Disconnect / forget credentials" on the Router screen.

## Permissions

- **Location (ACCESS_FINE_LOCATION)**: Android requires it before an app can read the Wi‑Fi
  network name. The app uses it **only** for that. It does not collect, store or transmit your
  geographic location.
- **Notifications**: to tell you on your device when a new device joins your network.
- **Network and Wi‑Fi state, Wi‑Fi multicast, Internet**: to scan your network, discover device
  names, and reach your router and devices on your local network.
- **Foreground service (data sync)**: to keep the optional traffic monitor running while you
  use it.

## Network connections

The app connects to devices on your own local network: scan probes, name queries, your router's
admin page, and any device you choose to open with "Open in browser". If you use Share or
Export, the text you choose is handed to the app you pick; we do not receive it.

## Google Play

The app uses Google's Play in-app update library to check whether a newer version is available
and to prompt you to update. That check is made to Google Play by the Google Play services on
your device, and Google handles it under [Google's Privacy Policy](https://policies.google.com/privacy).
We do not receive that information.

## Data sharing and sale

We do not collect your data, so there is nothing for us to sell or share. We do not use any
advertising or analytics service.

## Advanced (root) features

On rooted phones the app offers optional network‑administration tools: blocking or limiting a
device and monitoring traffic on the network you are connected to. They require root access that
you grant, run on your device, and do not send data off it. Use them only on networks you own or
are authorized to manage.

## Retention and deletion

- "Clear device history" in Settings removes the stored device list. The names and trust labels
  you set are kept, so they come back if the same device returns.
- "Disconnect / forget credentials" removes the saved router login.
- Uninstalling the app removes everything the app stored.

## Children

The app is a network utility for adults and is not directed at children.

## Changes

We may update this policy. The "Last updated" date above shows the latest version.

## Contact

For questions about this policy, contact the developer using the contact email shown on the
app's Google Play store listing.
