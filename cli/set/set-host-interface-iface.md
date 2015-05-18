## set host interface iface

### Usage

`stack set host interface iface {host}... {mac} {iface} [iface=string] [mac=string]`

### Description

Sets the logical interface of a mac address for particular hosts.

### Arguments

* `{host}`

   One or more named hosts.

* `{mac}`

   MAC address of the interface  whose logical interface will be reassigned

* `{iface}`

   Logical interface.


### Parameters
* `[iface=string]`

   Can be used in place of the iface argument.
* `[mac=string]`

   Can be used in place of the mac argument.

### Examples

* `stack set host interface iface compute-0-0 00:0e:0c:a7:5d:ff eth1`

   Sets the logical interface of MAC address 00:0e:0c:a7:5d:ff to be eth1

* `stack set host interface iface compute-0-0 iface=eth1 mac=00:0e:0c:a7:5d:ff`

   Same as above.


### Related
[add host](add-host)

