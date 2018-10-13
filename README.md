# aws_upload
create instance on aws EC2.
get SSH keyfile save in local computer.
get ip address of instance createtd.

Install Putty

open putty

go to session set ip and then port 22.

go to SSH/Auth/ and browse SSH keyfile from local computer.

go to session give specific naming.

save changes.

open files.

server open.

write command.






for python -

-->ec2-user             	-ec2user-user.

-->ps -eaf|grep uwsgi   	-for checking python files . optinal only for python code.

-->cd BOTNLP            	-for pulling directory.

-->git pull origin master  	-for pulling updated file from git.

-->git login

-->git password

--> sudo uwsgi --emperor /etc/uwsgi/vassals --uid ec2-user --gid ec2-user






for nodejs -

-->ec2-user              -ec2user-user.

-->ls                    - list of files.

--> ps -eaf|grep node    -for chacking node files.

-->kill process-id       -for killing running process.

-->cd BOTNode

-->git pull origin master

-->git login

-->git password

optional * -->vi filepath            -for checking files.

-->pm2 start server/server.js   -for checking update.
		OR
-->pm2 start path to file.js

-->exit()





 

