# neon-library
Library modules for the Neon programming language.

## mine.neon
This module is used to parse, and create RFC 822 / RFC 1521 compliant messages.

Supported Algorithms
* Base64
* UUEncode / UUDecode
* BinHex
* Quoted Printable

## rsa.neon
This module provides the basic RSA Encryption tools.

Includes the folloowing functions:
* Create RSA keys
* Encrypt / Decrypt RSA encrypted messages
* RSA Sign messages
* Validate RSA Signed messages

## sid.neon
Commodore 64 SID sound library for Neon

Includes all basic SID chip functionality including Commodore Basic 7 commands:
* Play
* Sound
* whatever I'm forgetting

Also includes a built in byte compatible .MUS file player.  You can load .MUS files right off your old C64 disks, and play then directly.

## ldm/ldm/mvi56.ext
## ldm/ldm/mvi69.ext
ProSoft MVI56E-LDM and MVI69E-LDM extension library.  Used for direct Backplane access in these modules.  NOTE: This must be cross-compiled with the ProSoft LDM toolchain before copying the actual library to the LDM module.

## datalogger.neon
Neon module for accessing a ProSoft PLX51-DLPlus-232 gateway.  Includes functions for:
* Downloading all available records in CSV fornat.
* Reset the record pointer / clear all pending records.
* Download Trend Data to CSv file
* General Status


