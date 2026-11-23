# Rind support

## Add a second account

Choose **Add account** again, select the same provider and give the connection a distinct name, such as Work or Personal. Each connection uses its own credential or reading file.

## A reading looks old

Open the account and check its update time, then refresh the dashboard. For a file connection, open the file in Files and check the export timestamp. A new phone refresh can still display an older reading if the Mac exporter has stopped or the folder has not synchronized. Mac setup instructions are in **Settings → Connect a Mac exporter**.

## A usage percentage is missing

A percentage needs both a usage value and a limit for the same period. Some APIs report only costs or request counts. Rind displays the amount the provider returned. Grok and Gemini consumer subscriptions can be tracked manually or through a compatible reading file.

## Check an alert

Turn on **Limit alerts** in Rind, choose the percentage and allow notifications in the device’s notification settings. Refresh an account with a current, metered reading. A crossing produces one alert for that quota window. Background checks follow the schedule iOS grants. Check Focus and Scheduled Summary if a delivered alert does not appear immediately.

## Set up Watch and widgets

Open Rind on the paired iPhone and Apple Watch. Enable **Share readings with Apple Watch** in Rind settings. For a widget or complication, use the system editor to choose Rind Usage or Next Reset and select the account. The Watch uses readings shared by the phone.

## Sync preferences

Sign in to your Apple Account on each device and enable iCloud preference sync in Rind on each one. Set up provider connections separately on each device. A stale or expired API credential can be replaced from the account’s Edit screen.

When reporting a problem, include the device model, OS version, Rind version, provider and tracking mode. Remove credentials and personal account information from screenshots.

## Contact support

[Open a support request](https://github.com/fgalego/rind-support/issues/new). Requests are public. Please omit credentials and personal account information.
