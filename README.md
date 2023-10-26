# shelld-zelt
Ömer babanın bize shell düzenele hediyeleri (her eve lazım)
nc de alınan sheller çok kötü geliyor bunları aşağıdan yukarıya doğru kullandıkça shell daha kullanışlı hale gelir.


6) service --status-all

5) find / -perm -u=s -type f 2>/dev/null

4) export SHELL=bash

3) export TERM=xterm

2) stty raw -echo; fg

1) python3 -c 'import pty; pty.spawn("/bin/bash")'
