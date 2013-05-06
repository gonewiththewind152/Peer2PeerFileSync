Peer2PeerFileSync
=================

Files syncing Peer-to-Peer, socket programming using Java
1. Extract the files into the folder you want to share
2. Using terminal (tested on linux and mac) navigate to the folder
3. Run: 
        javac sync.java        
To create the executable files. However, these files should already present in the zip folder.
4. To run the program, run the command: 
        java FileSync
This command will make your computer enter the network but not yet connect to any peers
If there are peers existing in the network you can run the following command to immediately connect to a specific peer:
        java FileSync <ip adress>
5. After entering the network there are 4 command that the user can use:
    1) show - print out all the connected peers
    2) connect <ip address> - connect to the specified ip address
    3) disconnect <ip address> - disconnect from the peer with the specified ip address
    4) quit - quit the program
Please note that the log result will continuously printed out but you can always enter these commands.
The show command only works if the server is on.


