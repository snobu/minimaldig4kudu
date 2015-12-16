# minimaldig4kudu
Minimal dig.exe and DLLs for running in Kudu


### Basic Usage ###

```bash
$ dig redhat.com +short
209.132.183.81


$ dig redhat.com ns +short
ns2.redhat.com.
ns3.redhat.com.
ns1.redhat.com.
ns4.redhat.com.


$ dig -x 209.132.183.81 +short
www.redhat.com.


$ dig +trace +short redhat.com
NS d.root-servers.net. from server 8.8.8.8 in 23 ms.
NS i.root-servers.net. from server 8.8.8.8 in 23 ms.
NS m.root-servers.net. from server 8.8.8.8 in 23 ms.
NS c.root-servers.net. from server 8.8.8.8 in 23 ms.
NS h.root-servers.net. from server 8.8.8.8 in 23 ms.
NS g.root-servers.net. from server 8.8.8.8 in 23 ms.
NS k.root-servers.net. from server 8.8.8.8 in 23 ms.
NS b.root-servers.net. from server 8.8.8.8 in 23 ms.
NS j.root-servers.net. from server 8.8.8.8 in 23 ms.
NS a.root-servers.net. from server 8.8.8.8 in 23 ms.
NS f.root-servers.net. from server 8.8.8.8 in 23 ms.
NS l.root-servers.net. from server 8.8.8.8 in 23 ms.
NS e.root-servers.net. from server 8.8.8.8 in 23 ms.
RRSIG NS 8 0 518400 20151226050000 20151216040000 62530 . Hk5KQmo5MrIg2GxwjPJ6BK
QkIsMItsLg75l4fUvycRnr59UyXS7GFB8g ZwJPOJMMr76ITomF29zXjzAdJYv2ANuMLRneV1M5v1WTj
o9Dt9lSbY4X 770jC2ozC0dvtODF01zlNPPfO2+Ar0iYZ8YnBE3vetolMO+Ubg9kPo6v rwg= from
server 8.8.8.8 in 23 ms.
A 209.132.183.105 from server 209.132.176.100 in 204 ms.
```
