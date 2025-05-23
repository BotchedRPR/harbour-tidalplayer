# Tidal player for Sailfish OS

This might be one day a Tidal Player for Sailfish OS using the tidalapi v0.7.1 (https://tidalapi.netlify.app/). 

### TIDAL API useage
As v0.7.1 is not fully compatible with TIDAL anymore, the line 114 of tidalapi/user.py is removed during the packaging process.

### Usage of AI
The current development is driven by Claude 3.5 Sonnet. The icon is made by Midjourney.

## Future Features

- Tidal account integration with OAuth authentication
- Browse and search Tidal's music library
- Create and manage playlists
- Play tracks, albums, and playlists
- Media controls (play, pause, next, previous)
- Track information display
- Album artwork display

## Requirements

Include https://openrepos.net/user/7598/repository and https://openrepos.net/user/2414/repository as repository:

or look for
Python3-request
and
Python3-future

in storeman and add the corresponding repos.

and 

- Python 3.x
- Qt/QML
- PyOtherSide
- Tidal API credentials

