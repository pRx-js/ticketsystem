# Version 2.0.3
#### Released 01.10.2020 (DMY)

## Bugfixes
- :bug: Fixed a bug where no Notification is being sent after a user answers a ticket
- :bug: Fixed a bug where /ticketteam would not send an error if a user has insufficient permissions
- :bug: Fixed a bug where sending /ticketteam without an action would throw no error for authorized users
- :bug: Fixed embed colour for error message if an user with insufficient permissions tries to use /ticketteam

## Dependency updates
- :arrow_up: Upgraded dependencies to newest version

## Removed Features
- :fire: Removed legacy check for me to be able to use /ticketteam without having the team-role

## Language
- :globe_with_meridians: Fixed a typo for English language pack

## UI and Style
- :lipstick: Log output regarding version checks are now colourized. If no update is available the output will be coloured green. If there is an update available or an error occurred while checking for a new version the output will be red.

## Documentation
- :memo: Added Changelog