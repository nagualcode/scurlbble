
# ScURLbble

ScURLbble is a Bash script for scrobbling and updating the "Now Playing" status on [Last.fm](https://www.last.fm). It leverages the Last.fm API to:

- Authenticate users.
- Scrobble tracks and Update the "Now Playing" status. 
- Manually or integrate with `mpc` (MPD Client).

## Prerequisites
- **Dependencies**:
  - `curl`: For API calls.
  - `md5sum`: For generating API signatures.
  - `mpd/mpc`: For music tracking (optional, if using the auto-scrobble loop).


- **Last.fm API Credentials**:
  - [Register a new application](https://www.last.fm/api/account/create) to get your `API_KEY` and `API_SECRET`.

---

## Usage

### Auto-Scrobble with `mpd / mpc`
./scurlbble 

or

### Scrobble a Single Track
./scurlbble "Artist" "Track" (manual mode)

The script will prompt for your Last.fm credentials (API key, API secret, username, and password) if missing and save to ./config.txt


---


## License
Free for all forever and ever!


