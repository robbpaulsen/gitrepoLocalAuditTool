# This script those exactly the same as "nicrefresher", but skips one step:

## First take down the NIC and then we tell macchanger to give it back the permanent MAC of the device, otherwise the NIC may brick itself or just plain start behaving like the MACADDRESS that macchanger assigned it.

* sudo ip link set eth0 down && sudo macchanger -p eth0 &&

## Then just put in back up again

* sudo ip link set eth0 up &&

## And at the end again printing the stdout so that the user may see the change

* ip a | awk '{print $2}' | grep 192.* | cut -b 1-12 &&

* echo "All Back to Normal!!"