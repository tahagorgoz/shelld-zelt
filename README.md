# shelld-zelt
ömer babanın bize shell düzenele hediyeleri (her eve lazım)

service --status-all

find / -perm -u=s -type f 2>/dev/null

export SHELL=bash

export TERM=xterm

stty raw -echo; fg

python3 -c 'import pty; pty.spawn("/bin/bash")'
