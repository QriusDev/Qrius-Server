# The Qrius Server Setup
My basic development server setup container to keep track of changes. (This will be updated later)

## Getting everything working
First, its important to note, (as I'm writing this) the current project is specifically geared toward my own setup but I'll give a general explanation in case someone wants to use adapt from it. For now, this might not be a noob friendly repo.

### First, Get Everything!
Clone your apps into the `/applications/` folder. Make sure your apps have Dockerfiles to use for docker-compose.

### *Tweak* *Tweak* Config
Modify the `/applications/nginx-reverse-proxy/nginx.conf` to suit your *reverse-proxy application routing needs*.

### Date with Docker (Eww!)
Do some *docker-compose-fu* to add your apps to the container(...group?). 

### Tl;DD (Too Long; Didn't Do)
If you don't have any projects to add, my portfolio is also open-source so you can just pull that in and it should be plug-n-play. Just remember to comment out the services that you aren't using in the docker-compose file!

### Run
Then run 
```
bash run-dev.sh
// or
bash run.sh
```
Based on your needs.
