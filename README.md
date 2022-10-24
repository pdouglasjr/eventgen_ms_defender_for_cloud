## Splunk event generator add-on for Microsoft Defender for CLoud

host = aio1\
index = mdc\
source = ms:defender:cloud\
sourcetype = ms:defender:cloud:alerts

Make sure to change host, index, source, and sourcetype values to match your Splunk environment.
