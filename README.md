#dnsdiff

Quickly suss out discrepancies between nameservers

#Usage 
`python dns_diff.py -n nameserver.dns1.net nameserver.dns2.net nameserver.dns3.net -d yourdomain.com`

Returns a system exit code of 0 if no discrepancies found, otherwise returns 1 