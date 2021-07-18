# networkingQuery4linux

## Ports and services

- Find all the process hoarding a specific port

`sudo lsof -t -i:PORT_TO_CHECK`

- Stop all the process hoarding a specific port

`// you can use the process id if you know it`

`sudo kill -9 $(sudo lsof -t -i:PORT_TO_CHECK)`

## execute permission to files
- Execute permission to files
`chmod +x script-name-here.sh`

- Running process in background with logs
`nohup Your_code_here`


