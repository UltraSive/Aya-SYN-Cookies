# Aya-SYN-Cookies
This project doesn't proxy traffic yet simply stores state of TCP connections using small hash values which are light on resources and can verify legitimate ACK acknowledgement responses when we ensure the hash wasn't modified. This will then allow the connection to ingress and utilize the resources required in the network stack.
