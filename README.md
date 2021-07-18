# networkingQuery4linux

## Ports and services

- Find all the process hoarding a specific port

`sudo lsof -t -i:PORT_TO_CHECK`

- Stop all the process hoarding a specific port

`// you can use the process id if you know it`

`sudo kill -9 $(sudo lsof -t -i:PORT_TO_CHECK)`

## Execute permission to files
- Execute permission to files

`chmod +x script-name-here.sh`

## Using Screen to run process in background

- start a screen session
<code>
 >_ screen
 >_ your_code_here
</code>
 
- list all the screen sessions
<code>
 >_ screen -ls
</code>

- see the running screen session again
<code>
 >_ screen r
</code>
