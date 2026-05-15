# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
## OUPUT - ARP
## PROGRAM - RARP
client.py
<img width="478" height="562" alt="image" src="https://github.com/user-attachments/assets/5bb71b77-1483-468d-bcd3-3a1889363ee7" />


server.py

<img width="528" height="241" alt="image" src="https://github.com/user-attachments/assets/e0eef8a4-cd2d-453c-868e-9c928518f1a3" />

## OUPUT -RARP
client.py

<img width="375" height="58" alt="image" src="https://github.com/user-attachments/assets/b5ca2593-66d0-4df1-90fa-ef10aa684a25" />


server.py
<img width="604" height="158" alt="image" src="https://github.com/user-attachments/assets/2f2e088d-22f6-4290-a6ee-feb18e4900a7" />

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
