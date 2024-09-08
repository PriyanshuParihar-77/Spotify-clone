**Spotify Clone - JavaScript Functionality**

This repository features JavaScript code for a Spotify clone, focusing on audio playback and dynamic UI updates. It demonstrates how to handle basic music controls and interface changes in a web application.

Key Features:
Initial Setup: On page load (DOMContentLoaded event), the banner is initialized with default content, including a default image, heading, and text.

playAll(songNumber) Function:

Purpose: Manages audio playback and updates the banner based on the selected song.
Behavior:
If the selected song is already playing, the function pauses the song and reverts the banner to its default state.
If a new song is selected, the function updates the audio source, plays the new song, and updates the banner’s image, heading, and text to reflect the new track.
playaudio() Function:

Purpose: Toggles the play/pause state of the audio.
Behavior:
If the audio is paused, it starts playing and changes the button icon to the pause symbol.
If the audio is playing, it pauses the track and changes the button icon to the play symbol.
How It Works:
On Page Load: The DOMContentLoaded event sets the default banner with a background image, a placeholder image, and generic text.
Play/Pause Control: The playAll function controls which song is played and updates the UI elements accordingly. It switches the banner’s content based on the song number, using hardcoded paths for images and text.
Toggle Play/Pause: The playaudio() function allows toggling between play and pause states, updating the play/pause button icon as needed.
Usage Instructions:
Integrate the Script: Include this JavaScript file in your HTML to enable functionality.
HTML Requirements: Ensure that your HTML document contains the necessary elements with corresponding IDs/classes as referenced in the script.
Media Files: Place your audio files and images in the specified directories to match the paths used in the script.
Feel free to enhance this basic functionality by adding features like playlists or more advanced UI elements!
