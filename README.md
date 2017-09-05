# dnsdiff

Quickly suss out discrepancies between nameservers

# Installation

`pip install dnsdiff`

`dnsdiff -n nameserver.dns1.net nameserver.dns2.net nameserver.dns3.net -d yourdomain.com`

Output:

    {   'lol.test':
    [   DNS name gina.ns.cloudflare.com.,

    DNS name will.ns.cloudflare.com.]}

    Determining differences

    No discrepancies found

# Usage 

    usage: dns_diff.py [-h] [-n NAMESERVERS [NAMESERVERS ...]] [-d DOMAIN]

    Quickly look up and compare NS records for a domain across multiple

    optional arguments:

      -h, --help            show this help message and exit
  
      -n NAMESERVERS [NAMESERVERS ...], --nameservers NAMESERVERS [NAMESERVERS ...]
  
      -d DOMAIN, --domain DOMAIN


Returns a system exit code of 0 if no discrepancies found, otherwise returns 1 
