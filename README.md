# keyssh-termux



- apt update 
- apt upgrade 

↓
- ssh-keygen

Generating public/private rsa key pair.
Enter file in which to save the key (/data/data/com.termux/files/home/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase):
Enter same passphrase again:

and you see SHA
+---[RSA 3072]----+
|          o+ .   |
|       . ..o*.   |
|      . + +o+.   |
|       . *.+ .o  |
|        S.o=.o o |
|       .+o*+= . .|
|        +=+*o. ..|
|         E.o+..o.|
|        o o.o+o..|
+----[SHA256]-----+

check ssh key : 
ls -al .ssh 
