# Today Photos Support

Today Photos finds photos taken on today's month and day across prior years, presents them in a chronological gallery, and prepares local thumbnails for Home Screen widgets.

## Contact

For support, bug reports, privacy questions, or feature requests, email [admin@nibrwr.me](mailto:admin@nibrwr.me).

Please include your device model, iOS or iPadOS version, Today Photos version, and a short description of what happened. Screenshots are helpful, but do not send private photos unless they are necessary to explain the issue.

## Photos Do Not Appear

1. Open **Settings > Privacy & Security > Photos > Today Photos** and confirm access is allowed.
2. Open Today Photos and leave it active while iCloud-backed photos finish downloading.
3. In Today Photos, open **Settings** and tap **Refresh Widgets** after adding photos or changing Photos access.

Today Photos can only show photos whose capture month and day match the selected date and that are included in the app's current Photos permission.

## A Widget Is Stale or Blank

Open Today Photos once to confirm the current day's gallery and widget cache are ready. In the app's Settings pane, **Widget Status** reports the cache state and **Refresh Widgets** rebuilds today's cache. Widget refresh timing is ultimately scheduled by iOS.

## Sharing Takes Time

The share button retrieves the original or best available full-size image before presenting Apple's share sheet. An iCloud-only photo can take longer because PhotoKit must download it first. Keep the app open until the system share sheet appears.

## Photo Locations

A map is shown only when the selected photo includes location metadata. Tapping the map opens a larger map with the available place name and coordinates. Today Photos does not request your current device location.

## Privacy

Read the [Today Photos Privacy Policy](today-photos-privacy.html).
