# python_artnet
simple python artnet script

UDP_test sends a byte array of hex values to a DMX ethernet bridge. In my case an ENTTEC OPENDMX bridge device connected between a raspberry pi and the ENTTEC via ethenet

UDP_receive receives UDP hex values from another PC and just forwards to the ENTTEC bridge. This was useful for me to read the artnet hex values used.
