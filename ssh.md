# ssh

Create ssh key

    ssh-keygen -t ed25519 -C "example@example.com"

Copy public key to remote server

    ssh-copy-id
  
Use ssh-agent in remote server

    exec ssh-agent bash

Start ssh agent

    eval $(ssh-agent -s)

Add key to agent

    ssh-add ~/.ssh/[key file]
    
Enable agent forwarding in the local ssh config

      ForwardAgent yes
      
Enable agent forwarding in the remote ssh server config

    vi /etc/ssh/sshd_config
    
Manage ssh server

    systemctl status sshd
    systemctl start sshd

Jump host

    ssh -J user@jumphost -R 8080:localhost:8080 user@hiddenhost
    ssh -R 8080:hiddenhost:8080 user@jumphost
