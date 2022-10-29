# nostr-libnotify

Monitor libnotify notifications and send them to nostr

## Environment variables

These must be set for the script to work:

- `NOTIFY_PK`: pubkey to be notified on critical alerts
- `RELAY_URL`: relay to send events to (eg. `ws://127.0.0.1:8080`)
- `NOSTR_KEY`: the nostr secret key to sign notifications
