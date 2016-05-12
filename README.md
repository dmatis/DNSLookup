# DNS Client

#### A DNS client for resolving a domain name to its associated IP address

## To Start:

0. Download entire project
1. Type *make* in the command line to run the provided Makefile

## To Run:

**From the command line, type:**<br />
*java -jar DNSlookup.jar rootDNS name [-t]*<br />

*rootDNS* is the root IP address that it should begin it's search (ie 198.41.0.4)<br />
*-t* is optional and enables tracing of the queries made and responses received<br />

## Sample Output:

name_being_looked_up time_to_live IP_address

ie. *198.162.35.1 www.cs.ubc.ca -t* will output:<br />
www.cs.ubc.ca 3600 142.103.6.5<br />
