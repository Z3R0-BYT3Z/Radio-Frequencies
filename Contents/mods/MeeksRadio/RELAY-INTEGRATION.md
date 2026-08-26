# Meeks Protocol relay integration

Radio Frequencies writes one clean server-log record per bulletin:

`[MeeksRadioBroadcast] [RADIO EMERGENCY] Message text`

Add `[MeeksRadioBroadcast]` to the bridge's recognized marker list. The text
after the marker is safe to forward to the configured Discord webhook. The mod
itself handles in-game chat and persistent per-station history.

