Windows command-line utility for remotely waking up computers by sending magic packets over the network.

## Features

- Directly specify the MAC addresses to wake up (multiple MAC addresses allowed)
- Use a text file containing MAC addresses to wake up (one MAC address per line)
- Destination IP address or destination UDP port number can be specified

## Package Parameters

- `/UseInf:` - Change the inno setup configuration file to use/save when installing

### Examples

`choco install wol`

`choco install wol --params "'/UseInf:C:\wol.inf'"`