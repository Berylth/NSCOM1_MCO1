# NSCOM1 MCO1: TFTP Client for Tftpd64
Implementation of a Trivial File Transfer Protocol (TFTP) client for Tftpd64, adhering to the specifications outlined in RFC 1350. The client is developed using Java's DatagramSocket class, which facilitates communication over UDP (User Datagram Protocol). The program supports Read Requests (RRQ) and (WRQ) Write Requests and also handles other TFTP packets such as DATA, ACK, ERROR, and OACK. 

## Pre-requisites
1) Code Editor
2) Java
3) [Tftpd64](https://pjo2.github.io/tftpd64/)

## How to run
1) Download Tftpd64 and the java program in com/tftp/Client.java.
2) Enable TFTP service in the setting of Tftpd64.
3) Choose a base directory in the Tftpd64 to store the folders.
4) Compile the java program using the command:
    ```
    javac Client.java
    ```
5) Run the java program using the command:
    ```
    java Client
    ```

## Members
- Loja, Kyle Flor
- Magura, Bryle Jhone R.

## Acknowledgements
- This project is based from [RFC 1350](https://www.rfc-editor.org/rfc/rfc1350).
- Thanks to the creator [Tftpd64](https://pjo2.github.io/tftpd64/) for the free and open source networking tool.
