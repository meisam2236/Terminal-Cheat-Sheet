| Command | Action |
| ------- |:------:|
| `cd /folder/` | choose directory |
| `cd ~` | choose directory home |
| `cd ..` | choose directory of one step back |
| `ls /folder/` | list files |
| `ls -la` | list files including hidden ones |
| `cp file.txt /destination/` | copy file to destination |
| `cp -R /folder/ /destination/` | copy directory  |
| `ditto -V /folder/ /destination/` | copy contents of a folder to a new folder |
| `mv file.txt /destination/` | move file |
| `mv -i file.txt /destination/ `| move file with permission asking |
| `mv oldfilename.txt newfilename.txt` |rename file |
| `touch <file>` | make an empty file |
| `mkdir <folder>` | make a directory |
| `rm <file>` | remove file |
| `comm <file1> <file2>` | compare two sorted files line by line |
| `diff <file1> <file2>` | display differences in the files |
| `du /destination/` | disk usage |
| `du -sh /destination/` | disk usage(sh stands for summary human readable) |
| `df -h` | disk free space(h stands for human readable) |
| `free` | show free ram |
| `grep ftp /etc/*` | find the word 'ftp' in all the files in /etc/ destination |
| `find /destination/ -name <file>` | find files with specific name |
| `open <file>` | open files or directories simultaneously|
| `open -a Preview file.pdf` | open pdf file with preview |
| `nano <file>` | open file with nano text editor |
| `wget 'https://www.example.com'` | get files from web(web get) |
| `sudo <command>` | superuser's command |
| `pwd` | print working directory |
| `top` | sohw the processes |
| `htop` | interactive process viewer |
| `kill <PID>` | kill by processor's ID |
| `man <command>` | manual of the command |
| `whatis <command>` | get one-line description for a command |
| `tar -cf compressed.tar <file>` | compress file |
| `tar -xvf compressed.tar` | extract tar file(v is for listing) |
| `tar -czf file.tar.gzip <file>` | compress with tar and gzip |
| `tar -cjf file.tar.bz2 <file>` | compress with tar and bz2 |
| `tar -xzf file.tar.gzip <file>` | extract tar.gzip file |
| `tar -xjf file.tar.bz2 <file>` | extract tar.bz2 file | 
| `zip <file>` | zip file |
| `unzip <file>` | unzip file |
| `reboot` | reboot |
| `startx` | activate graphical user interface |
| `shutdown -h now` | shutdown now(h reffers to halt) |
| `shutdown -h +30` | shutdown after 30 seconds |
| `shutdown -r +20&` | restart after 20 minutes |
| `shutdown -r 11:24` | reboot pc in 11:24 |
| `shutdown -c` | cansel shutdown |
| `mount -t iso9660 <iso file> /mnt/cdrom` | mount the iso file(like disk) |
| `ifconfig` | interface configuration |
| `sudo apt update` | update apt list |
| `sudo apt upgrade` | update softwares |
| `sudo apt install <software>` | install software |
| `clear` | clear texts |
| `users` | show users |
| `whoami` | show name of user |
| `finger <user>` | information of user |
| `passwd` | change password |
| `exit` | back to user(not superuser) |
| `uname -a` | specify the linux we are using |
| `ip addr` | ip address |
| `adduser <user>` | add a user |
| `useradd <user>` | add a user |
| `deluser <user>` | delete a user |
| `userdel <user>` | delete a user |
| `passwd <user>` | change password of a user|
| `ps -A` | list of all opened programmes |
| `killall <program name>` | close all programmes with name |
| `ps -cux` | list of all opened programmes (more precise) |
| `chmod rwxrwxrwx <file>` | change mode read write execute for the 1.owner,2.related users to owner,3.everyone else |
| `chmod 774 <file>` | change mode read write execute for the owner, related users to owner and just read for everyone else(r=4 w=2 e=1) |
| `chown <user> <file>` | make user the owner of the file |
| `lsusb` |	shows all usb devices mounted |
| `lspci` | shows all the devices connected with pci |
| `lshw` | shows all the hardware devices |
| `lshal` | shows all hal(Hardware Abstraction Layer) |
| `lsmod` | shows kernel modules |
| `cd /media` |	shows medias like usb |
| `cd /mnt` | shows mounted devices like usb |
| `pstree` | shows running app in tree shape |
| `runlevel` | shows the runlevel you are in |
| `telinit 3` | goes the third runlevel |
| `wall <message>` | give messages to others |
| `initctl` | shows all the services running |
| `service <name of service> stop` | stop the service |
| `service <name of service> start` | start the service |
| `service <name of service> status` | status of the service |
| `systemctl` | like initctl |
| `fdisk /dev/sda` | fdisk |
| `parted /dev/sda` | parted |
| `gparted` | graphical interface of parted |
| `history` | list of commands history |
| `cal` | calendar |
| `ping example.com` | ping website |
| `hostname` | show hostname |
| `hostname -i` | show ip address of network |
| `iptables` | show incomming and outgoing internet traffic |
| `echo <text> >> <file>` | echo text to the file |
| `echo $PATH` | echo path environment |
| `curl example.com` | download example.com |
| `curl ftp://example.com` | download using ftp protocol |
| `curl -O example1.com example2.com` | download more than one url |
| `curl -o <file> http://example.com` | saving url to file |
| `curl -C -O http://example.com` | continue downloading |
| `curl https://example.com -H "Accept: application/json"` | JSON GET method(h stands for header) |
| `curl -X DELETE http://example.com/json?id=1 -H "Accept: application/json"` | JSON DELETE method | 
| `curl -X POST https://example.com -H 'Content-Type: application/json' -d '{"login":"my_login","password":"my_password"}'` | JSON POST method(d stands for data) |
| `curl -X POST https://example.com -H "Content-Type: application/x-www-form-urlencoded" -d "param1=value&param2=value2"` | JSON POST form method |
| `curl -k https://example.com` | ignore SSL certificate errors |
| `curl https://example.com -H "Accept: application/json" -H "Authorization: Bearer {token}"` | JSON GET method with Bearer Token Authorization Header |
| `ssh <user>@<ip address>` | connect to server |
| `scp <file> <user>@<ip address>:/directory/` | copy file to remote server |
| `scp -r <folder> <user>@<ip address>:/directory/` | copy folder to remote server |
| `scp <user>@<ip address>:/directory/ /directory` | copy a remote file to local system |
