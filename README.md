# macpipe

Small utility which exchanges macsec keys with ethernet frames. 

Adjust macpipe.ini and set address, interface and shared secret:

```
my_address=10.100.0.1/24
my_interface=enp0s31f6
shared_secret=11223344
```

Then execute macpipe.py:

```
sudo python3 macpipe.py
```

## prerequisites

Install python3 scapy and cryptography libraries:

`sudo apt install python3-scapy python3-cryptography`

Note that this code contains fifo functionality currently unused.
