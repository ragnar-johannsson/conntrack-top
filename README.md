## Top utility for the nf_conntrack table

A script that calculates the top 10 source and destination addresses in Netfilter's connection tracking table for UDP and TCP.


### Usage

```
$ conntrack_top

Connection count:   3801
Connections max:  296608

Top TCP
Source              Num    Destination         Num
192.168.1.46        207    192.168.1.30        967
85.220.x.x           75    91.192.x.x          963
192.168.1.30         40    192.168.1.196       209
93.179.x.x           32    192.168.1.21         16
86.152.x.x           32    77.109.x.x           14
17.120.x.x           31    192.168.1.46         12
192.168.1.196        31    14.192.x.x            8
157.157.x.x          27    194.144.x.x           8
212.30.x.x           24    192.168.1.138         7
192.168.1.72         23    192.168.1.81          7

Top UDP
Source              Num    Destination         Num
69.122.x.x          164    192.168.1.55        283
192.168.1.63        140    12.122.x.x          282
192.168.1.30         31    47.201.x.x          183
192.168.1.72         23    192.168.1.72        144
37.189.x.x            9    192.168.1.1          46
192.168.1.46          9    192.168.1.63         38
192.168.1.208         6    188.51.x.x            8
192.168.1.196         5    31.172.x.x            4
174.55.x.x            4    81.229.x.x            3
189.47.x.x            4    87.122.x.x            3

$
```


### License

Simplified BSD. See the LICENSE file for further information.
