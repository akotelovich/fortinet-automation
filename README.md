Output Fortigate rules into CSV file:
```
name;uuid;srcaddr;dstaddr;action;status;service;comments;
16;'';3e9763a8-607c-51ef-457b-1f6e56830616;"all";"10.99.99.99_32";deny;enable;"ALL";"Comment1";
33;'';43c7c01a-4938-51ec-08ea-e8541bebdf6b;"Host1_10.9.77.20" "Host2_10.1.78.20";"All_RFC1918";accept;enable;"ALL";"Comment2 (2024-08-27);
62;"Rule_allow_ALL";9b2f01ea-d0c4-51ee-649e-d8a8e62451f7;"Host3" "Host5";"n-10.10.0.0_16" "n-10.11.0.0_16";accept;enable;"RDP" "SMB" "SSH" "TCP-135";'';
```