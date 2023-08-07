to connect to aws ssh terminal - 
$ ssh -i todo-class.pem ubuntu@ec2-3-86-84-63.compute-1.amazonaws.com

to check the read and write permission(if there are too many aws may refues to connect) -
$ ls -ltr todo-class.pem 
-rw-r--r-- 1 RAHUL 197121 1678 Aug  6 19:25 todo-class.pem

to change the permission to just you (revoke other user permission ) -
$ chmod 600 todo-class.pem

checking again -
$ ls -ltr todo-class.pem 
-rw------- 1 RAHUL 197121 1678 Aug  6 19:25 todo-class.pem

clone your repo here -
$ git clone https://github.com/Rahu09/week-9.git

install nvm (to install node and run npm command) -
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

ran last three command from the that recommended -

then installed node -
$ nvm install node

installed modules - 
$ npm i