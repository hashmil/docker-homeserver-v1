# Docker reciepe for a media homeserver

1. Clone this repo
   `git clone https://github.com/hashmil/docker-homeserver-v1.git`

2. Navigate to the repo folder
   `cd docker-homeserver-v1`

3. Pull required files and services from docker
   `docker-compose pull`

4. Launch it
   `docker-compose up -d`

- To shutdown
  `docker-compose down`

## Ports Used

These can be changed in the `docker-compose.yml` file.
These should work as `http://localhost:[port number]` - or replace `localhost` with your local IP address.

- homarr: 80
- plex: 32400/web
- sonarr: 8989
- radarr: 7878
- jackett: 9117
- transmission: 9091
