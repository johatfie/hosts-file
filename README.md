# hosts-file

This repo contains the Windows hosts file with entries for my Widgets Are Us microservices project.  The purpose of this repos is to allow easy changes from localhost to docker by changing branches.  So, http://config-server:8071 with either point to http://localhost:8071 or http://192.168.99.100:8071 depending on which branch this repo is on.  This repo should be placed in the C\Windows\System32\drivers\etc folder replacing the existing hosts file.
