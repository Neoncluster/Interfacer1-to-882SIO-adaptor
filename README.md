# Interfacer 1 to 882SIO adaptor
A small adaptor card to make an S-100 Compupro Interfacer 1 card perform as an Altair 882SIO card. This allows for greater compatibility with a larger array of comms software.

<img width="820" alt="Screenshot 2023-02-23 at 11 04 30 PM" src="https://user-images.githubusercontent.com/61561950/220876731-1ecf25c7-e663-424d-a691-065eca725a0e.png">

First build the adaptor board:
1) First install pin headers (machined type) on the right as viewed from the solder side.
2) Install sockets on the right as viewed from the parts side.

To complete the install do the following:

3) Remove IC26, IC27 and IC28 from the Interfacer 1 board 
4) Insert IC26, IC27 and IC28 into your built up adaptor board
5) Insert adaptor board back into IC26, IC27 and IC28 empty sockets
6) Pull IC 22 from its socket, and gently bend pins 4 and 12 so that they do not go into the socket. Put the chip back in the socket that way.
7) On the solder side of the board, solder a wire from IC14-9 to IC14-10
8) On the solder side of the board, solder a wire from IC12-9 to IC12-10

<img width="400" alt="Screenshot 2023-02-24 at 12 08 14 AM" src="https://user-images.githubusercontent.com/61561950/220889849-090836fd-3462-461d-9fe4-7e3cd422cd58.png">

<img width="400" alt="Screenshot 2023-02-24 at 12 07 59 AM" src="https://user-images.githubusercontent.com/61561950/220889880-decc1a34-53f7-4441-935b-529bc110ce38.png">
