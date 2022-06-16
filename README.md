# Simple-NetCat-module
A Basic NetCat module that can be implemented in a server
Usage:
                netcat.py -t 192.168.1.108 -p 5555 -l -c # command shell
                netcat.py -t 192.168.1.108 -p 5555 -l -u=mytest.txt # upload a file
                netcat.py -t 192.168.1.108 -p 5555 -l -e=\"cat /etc/passwd\" # execute commmand
                echo 'ABC' | ./netcat.py -t 192.168.1.108 -p 135 # echo text to server port 135
                netcat.py -t 192.168.1.108 -p 5555 # connect to server
