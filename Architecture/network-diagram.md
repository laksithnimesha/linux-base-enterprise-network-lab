

```
                    Internet
                        |
                Firewall / Gateway
                  192.168.10.1
                        |
          --------------------------------
           Internal Network 192.168.10.0/24
                        |
     ------------------------------------------------
      |               |             |               |
    DNS             WEB           DB             FILE
192.168.10.10   192.168.10.20  192.168.10.30  192.168.10.40
   Bind9       Apache + PHP      MariaDB        Samba
                        |
                    Client VM
                 192.168.10.100
```
