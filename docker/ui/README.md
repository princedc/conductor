# Docker
## Conductor UI
This Dockerfile create the conductor:ui image

## Building the image
`docker build -t conductor:ui .`

## Running the conductor server
 - With localhost conductor server: `docker run -d -t conductor:ui`
 - With external conductor server: `docker run -d -t -e "WF_SERVER=http://conductor-server:8080/api/" conductor:ui`
