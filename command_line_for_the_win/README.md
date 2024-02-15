## Bash Scripting

# Background Context

[CMD CHALLENGE](https://cmdchallenge.com/) is a pretty cool game challenging you on Bash skills. Everything is done via the command line and the questions are becoming increasingly complicated. It’s a good training to improve your command line skills!

- I have included the screenshots of the challenge both in jpg and png format

# SFTP 
- Secure File Transfer protocol - Used to securely transfer files from a local machine to a remote one

** How to connect **

sftp [-oPort=customport] user@ip-address

- user - The username of remote host
- ip-address - ip address of the remote host

It the asks for user password to connect

# Uploading files to remote machine

sftp> put filename /path to remote host
- copy individual files to remote machine

sftp> put -r dir /path 
- copy directory and it contents recursivly
