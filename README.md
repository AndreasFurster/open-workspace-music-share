# Open Workspace Music Share (OWMS)
Tool for sharing music/sound in an (open) workspace.

## OWMS Host
A windows service that will play sound from one client. 
It communicates with all clients. There is no UI for this application. You can however install OWMS Client on the same machine as the Host.

## OWMS Client
A Windows application to control OWMS Host. Multiple clients can control the same Host. 
The application also contains a virtual output device for streaming sound to the Host. 

Features:
- Select host
- Play/pause
- Previous/next
- Volume control
- Select client for music playback
- View current playing song
