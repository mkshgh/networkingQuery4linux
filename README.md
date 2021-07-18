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

## Running code in background using jobs

- run a job in background
<code>
 #just end with an & at the end
  
  your_code_here &
</code>

- view all jobs
<code>
 #just type jobs
  
  jobs
</code>

- bring the job to foreground
<code>
 #type jobs and find your job number
  
  fg your_job_number
</code>

- Stop the job
<code>
 #type jobs and find your job number
  
  jobs your_job_number
</code>


- send the job to background again
<code>
 #type jobs and find your job number
  
  bg your_job_number
</code>

</code>



