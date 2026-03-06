[ec2-user@ip-172-31-36-171 home]$ sudo -i
[root@ip-172-31-36-171 ~]# cd /home
[root@ip-172-31-36-171 home]# chmod 764 /home/demo.txt
[root@ip-172-31-36-171 home]# ls -lthr
total 0
drwx------. 4 ec2-user ec2-user 146 Mar  3 19:07 ec2-user
-rwxrw-r--. 1 root     root       0 Mar  6 15:52 demo.txt
