PLD Configuration management, SSH and Web Server.

The following scripts:
How to connect through SSH.
How to transfer a file using SCP.
How to use SFTP to transfer more than 1 file/directory.
Restart some service.
Let you to connect just typing “ssh my_server”

Contain a certain commands to work with some servers services, how they work?
<h3>connect through SSH:</h3> Receive 3 parameters(IP, USER, PRIV_KEY) to stablish connection

`./connect-ssh ip user path_priv_key`

<h3>Transfer file:</h3> Receive 5 parameters(IP, USER, PRIV_KEY, PATH_FILE, DESTINY_PATH) to transfer files and work in two ways:
- Receiving 4 parameters: Transfer the files to the HOME server path 
- Receiving 5 parameters: Transfer the files to a specific server path 

`./tranfer-file ip user path_priv_key name_file destiny_file`




