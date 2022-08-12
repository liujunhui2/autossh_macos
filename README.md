# autossh in Macos
Enable autossh service with launchctl in Macos (plist)

## Files
Put com.user.sshtunnel.plist in ~/Library/LaunchAgents

## Install

`launchctl load com.user.sshtunnel`

## Manually start

`launchctl start com.user.sshtunnel`

## Stop

`launchctl stop com.user.sshtunnel`

## Remove

`launchctl remove com.user.sshtunnel`
