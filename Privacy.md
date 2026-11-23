# Rind privacy

Rind stores the account names, provider choices and usage readings you enter on your device. Rind has no developer-operated backend, advertising SDK or analytics SDK.

**Provider connections.** When you set up an automatic API connection, Rind sends the configured credential directly to that provider over HTTPS to request the report. The provider processes the request under its own privacy policy. Credentials and permissions to open chosen files are stored in the device Keychain. Manual tracking works offline.

**Reading files.** The Mac exporter writes usage windows, reset times and a timestamp to the file you choose. If you place it in a cloud folder, that folder provider synchronizes it according to your settings.

**Widgets, Watch and notifications.** Widgets read a local snapshot. When Watch sharing is enabled, Rind sends account names and readings to your paired Apple Watch. Alerts and Live Activities can show account names and usage on your Lock Screen. You can control these features in Settings.

**iCloud.** If you enable preference sync, Apple stores Rind settings in your iCloud account. Provider credentials, account names and usage reports are excluded from preference sync.

**Removing data.** Remove a connection from its account details to delete its local reading and associated Keychain item. Delete any exported file separately from the folder where you saved it. Revoking an API credential is managed by the provider.
