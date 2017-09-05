# dnsdiff

Quickly suss out discrepancies between nameservers

# Usage 

usage: dns_diff.py [-h] [-n NAMESERVERS [NAMESERVERS ...]] [-d DOMAIN]

Quickly look up and compare NS records for a domain across multiple

optional arguments:
  -h, --help            show this help message and exit
  -n NAMESERVERS [NAMESERVERS ...], --nameservers NAMESERVERS [NAMESERVERS ...]
                        A list of the nameservers you want to test
  -d DOMAIN, --domain DOMAIN

`python dns_diff.py -n nameserver.dns1.net nameserver.dns2.net nameserver.dns3.net -d yourdomain.com`

Returns a system exit code of 0 if no discrepancies found, otherwise returns 1 
