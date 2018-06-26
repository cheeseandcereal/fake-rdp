# Fake RDP
Simple program to emulate the handshake of an RDP server with python.

Sends an init packet with the fingerprint emulated from an NLA-enabled RDP server.
This will make it so that clients trying to connect to this server via RDP will be prompted for credentials, then get an error when trying to authenticate.

## Usage
This will run on both python 2 and 3

`./fake_rdp.py`
