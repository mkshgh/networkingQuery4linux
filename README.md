# networkingQuery4linux

## Ports and services

- Find all the process hoarding a specific port

`sudo lsof -t -i:PORT_TO_CHECK`

- Stop all the process hoarding a specific port

`// you can use the process id if you know it &nbsp`

`sudo kill -9 $(sudo lsof -t -i:PORT_TO_CHECK)`
