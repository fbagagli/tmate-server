# tmate-server
Tmate local server setup

## Server side

Prerequisite: docker, docker-compose

Steps:
1. Generate keys and create a .tmate.conf file to be used on client side
2. Setup the compose file with the correct ip of the serve and the chosen port

## Client side

Prerequisite: use tmate >= 2.4.0 (download from https://tmate.io/)

Steps:
1. Copy the .tmate.conf file created on the previous step (server) in our home
2. run 'tmate' and share the session, enjoy!
