**Tic Tac Toe in Python**
========================
Introduction
------------------------
Tic Tac Toe Online in Python is a socket-based Client-Server application in Python that allows multi-players to connect to the server and play Tic Tac Toe online with other players.  


Manual
------------------------
Tic Tac Toe Online in Python is a cross-platform game that should work on any modern desktop operating systems. The instructions below are demonstrated on a Linux distro, but you should be able to run this on Windows and Mac OS X as well.  

To use the server, directly run tic_server.py with python3.
                     
        python3 tic_server.py
* After you will ask to enter the port, simply enter: **8080**

To use the client, directly run tic_client.py with python3.

            python3 tic_client.py
* Make sure you will run tic_client.py on two different terminal windows to start the game. 
* For the address enter: **localhost**
* For the port enter: **8080**
* After every match server will ask for the play match again. If the user type "y" or" Y" then the server will not stop. We need to run the client again.
* If the user enter "n" or "N" then the servere will be closed.


Author
------------------------
* Yatin Baluja
