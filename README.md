## sipping- utility for sending SIP Options packets and received answer from endpoint.
#### For example usage
#### $1 - remote IP sip server (endpoint)
#### $2 - remote PORT sip server (endpoint)
#### $3 - local IP sip agent
#### $4 - local PORT sip agent
#### vuser: SIP FROM header packet
#### vdt: current date

`./sipping.py -r sip-options.txt -d $1 -p $2 -S $3 -P $4 -c 1 -i 2 -vuser:bdt -vdt:date`

#### Typical answer success pinging

```
sent Request OPTIONS to 10.126.45.208:5108 cseq=0 len=555
received Response 200 OK from 10.126.45.208:5108 cseq=0

1 packets transmitted, 1 packets received, 0.0% packet loss
```
