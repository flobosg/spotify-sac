# spotify-sac
## “Stop after current” implementation for Spotify Linux using D-Bus.

This script has only been tested in Spotify version 1.0.25.127 running on Ubuntu 14.04. It's a quick and dirty implementation, but it should work fine in most cases.

## Dependencies

* xdotool

## Usage

1. Run the `spotify-sac` script while Spotify is open and playing.
2. If the script is running, Spotify will stop playing (actually, it will pause) after the current song is finished.
3. To cancel the monitoring, kill the script with `Ctrl-C`.
