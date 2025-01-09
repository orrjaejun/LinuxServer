--- LINUX SERVER ---
Docker-compose version v2.4.1

Containers based on - dokken/centos-stream-9

--compose version v2.4.1

##curl url
 curl -SL "https://github.com/docker/compose/releases/download/v2.4.1/\
docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

#compose permission
 chmod u+x /usr/local/bin/docker-compose

##auto-completion 
curl -SL \
https://raw.githubusercontent.com/docker/compose/1.29.2/contrib/completion/bash/\
docker-compose -o /etc/bash_completion.d/docker-compose

2025.01.09