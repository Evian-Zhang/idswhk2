# IDS Homework 2

If snort see two packes in a flow with

* first packet has "login" or "Initial" in payload, destination port is 3399;
* and second packet has a "IPv4Address:Port" string(E.g. 123.45.6.7:8080) in payload, destination port is 3399;
* output an alert with msg "bot founded" and sid 1000001