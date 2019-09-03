---   
title: Resources   
---   
## Anycast Testbed
### [www.anycast-testbed.com](http://www.anycast-testbed.com)

The anycast research testbed has been created within the context of the projects SAND and DAS, a consortium consisting of the University of Twente, SIDN Labs, NLnet Labs, and SURFnet.

The testbed currently in expansion and already has several locations either operational or being installed.

Address prefixes and ASN resources have been allocated by SURFnet and RIPE NCC.

#### Legacy but still in use IP-BLOCKS 
<pre>
IPv4: 145.90.8.0/24
IPv6: 2001:678:d0::/48
ASN 1133 (temporary being used from the University of Twente)
</pre>

#### New AS and IP-BLOCKs to being used after 2020
<pre>
IPv4: 145.100.118.0/23
IPv6: 2001:610:9000::/40
ASN 1149 ANYCAST-TESTBED allocated by RIPE NCC
</pre>



## Verfploeter: Active Measurement of Anycast Catchments
### [https://ant.isi.edu/software/verfploeter](https://ant.isi.edu/software/verfploeter/index.html)

IP anycast provides DNS operators and CDNs with automatic fail-over and reduced latency by breaking the Internet into catchments, each served by a different anycast site. Unfortunately, understanding and predicting changes to catchments as anycast sites are added or removed has been challenging. 

Current tools such as RIPE Atlas or commercial equivalents map from thousands of vantage points (VPs), but their coverage can be inconsistent around the globe. 

Verfploeter purpose a new method that maps anycast catchments using active probing and provides around 3.8M passive VPs, 430 times the 9k physical VPs in RIPE Atlas, providing coverage of the vast majority of networks around the globe. 

Verfploeter has been used to evaluate the new anycast deployment for B-Root, and we also report its use of a nine-site anycast testbed. 

We show that the greater coverage made possible by Verfploeter’s active probing is necessary to see routing differences in regions that have sparse coverage from RIPE Atlas, like South America and China.

