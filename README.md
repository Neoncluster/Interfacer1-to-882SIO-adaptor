# Interfacer1-to-882SIO-adaptor
A small adaptor card to make an S100 Compupro Interfacer 1 card act like a Altair 882SIO card

<img width="433" alt="Screenshot 2023-02-23 at 10 59 11 PM" src="https://user-images.githubusercontent.com/61561950/220875649-7f7477ab-ce0d-41ad-a309-bbb7775a2514.png">

<img width="820" alt="Screenshot 2023-02-23 at 11 04 30 PM" src="https://user-images.githubusercontent.com/61561950/220876731-1ecf25c7-e663-424d-a691-065eca725a0e.png">


replaced the following wiring Instructions:
Rework to configure Interfacer-1 as 88-2SIO:
Swap the status register ready line bits, both ports:
1) Pull IC27 from its socket, and gently bend pins 7 and 13 so that they
do not go into the socket. Put the chip back in the socket that way.
2) Pull IC28 from its socket, and gently bend pins 7 and 13 so that they
do not go into the socket. Put the chip back in the socket that way.
3) Solder a wire from IC28-7 to IC27-7 to IC26-8 (I mean the actual IC
pins, not the IC sockets!!)
4) Solder a wire from IC28-13 to IC27-13 to IC26-6 (I mean the actual IC
pins, not the IC sockets!!)
Disable the control ports:
5) Pull IC 22 from its socket, and gently bend pins 4 and 12 so that they
do not go into the socket. Put the chip back in the socket that way.
6) On the solder side of the board, solder a wire from IC14-9 to IC14-10
7) On the solder side of the board, solder a wire from IC12-9 to IC12-10
Set the port addresses:
Set up S2 (port A address) with all switches closed except switches 4 and
8, which should be open
Set up S3 (port B address) with all switches closed except switches 1, 4
and 8, which should be open
Set the baud rate on S1
Disable the handshake lines:
Remove the jumpers from pins 3, 4,5 and 6 on both J3 and J5. (Only
jumpers on 1 & 2, crossing as they already are)

![117987274_2482615775362880_2258502236392704751_n](https://user-images.githubusercontent.com/61561950/220876186-95d266cf-408b-4f75-b9a2-6dd3bbebcb4d.jpg)
<img width="669" alt="Screenshot 2023-02-23 at 11 05 26 PM" src="https://user-images.githubusercontent.com/61561950/220876671-91143d0b-0cac-45c6-8b4f-73f6d3630e79.png">

