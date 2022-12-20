# WSL

Moving WSL instance to another drive:

    cd D:
    mkdir wsl
    cd wsl
    wsl --export [distro name] wsl-tmp.tar
    wsl --unregister [distro name] 
    wsl --import [distro name] [distro location] wsl-tmp.tar
    
Search registry `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Lxss` for imported distro and set `DefaultUid` to 1000 (decimal).
