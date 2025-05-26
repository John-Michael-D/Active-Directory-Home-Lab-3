**Project #3(A-K) - Applying and Testing GPO; Joining Client to Domain**
- The purpose of this project was to test the GPOs created in Project #2 on another VM.
- This project involved creating a client VM and joining it to the MegaCorp.local domain.
- First, the server VM had to be issued a static IP address along with a subnet mask and gateway address.
- Second, the server VM's loopback address was used as the preferred DNS server.
- The result of this is that any clients connected to the server VM will use the server VM itself as their DNS server.
- After the client VM was sucessfully joined to the server VM and the MegaCorp.local domain, the GPOs created in Project #2 were tested.
- The GPO update needed to be forced in the commandline. Then, the GPOs were successfully applied to the client VM.
