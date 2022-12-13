# etc file configuration

enable NOPASSWD for sudo group, for example, in combination with login via ssh key:

    in /etc/sudoers
    %sudo  ALL=(ALL) NOPASSWD: ALL
  
for a specific user

    username ALL=(ALL) NOPASSWD: ALL
  
