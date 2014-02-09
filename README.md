RPi-MFRC522-C
=============

Raspberry Pi C Library to interact with RFID MFRC522 board.

Description
===========

This is a preliminary version of Raspberry Pi C Library to manage an MFRC522 RFID board.
With this library you can:
  - Interact with MFRC522 registries as described in manufacturer datasheet.
  - Interact with the MIFARE cards as described by the MIFARE Standard.

Before the first stable release, we revisit the code from the point of view of performance. 


Setup procedure
===============

In order to compile the C Library, you need the bcm2835 library. You can donwload it from http://www.airspayce.com/mikem/bcm2835/
In this site you can found the instuction to download and install it in a Raspberry Pi board.

Remember to include the bcm2835 library when you compile you code (use the -lbcm285 parameter).
