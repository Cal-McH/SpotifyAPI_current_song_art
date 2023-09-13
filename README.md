# Spotify_current_album_art
Extracts the current playing songs album art from the Spotify API. This uses the current playing song API to extract the current playing song info and plots the album art for the song. There is also a parameter named 'pixel' in the album art function which converts the album art to a pixelated 64x64 version.

# Prerequisits

You will need to go on to the spotify API dashboard (https://developer.spotify.com/dashboard) and create a new app. Then get your client ID and secrete ID and paste these into the client_id and client_secret variables. 

After running, a webpage will open to give you the 'code' for the access token. Paste everything after the 'code=' from the URL unto the code variable.

After this, the function should be able to access the current song you are playing (as long as your spotify developer API and spotify music account are linked).

# Required Packages

- requests
- time
- pprint
- urllib.parse
- base64
- webbrowser
- skimage
- matplotlib.pyplot
- PIL
- numpy
