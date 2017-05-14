# structured-protocol-proxy
POC: Serialized Multi-Protocol Proxy (socket, inetd, http)

## Notes

Decode XML/WBXML/etc.. and serialize to preferred standard

Handle protocol level headers and multi-headers (dict/multidict)

clientA -> nginxA -> sppA -> script -> sppA -> nginxA -> serverA (and back again)
