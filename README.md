Rename all sub-folders in processing directory (sub-folder example:
./10.0.17.146_pid100) to GUID instead of 'pid100'
result: (./10.0.17.146_123ED8A6-095D-11E7-A571-68C46F4C87A2)

Example for single folder:
mv /home/ftp_user218/10.0.17.146_pid100
/home/ftp_user218/10.0.17.146_123ED8A6-095D-11E7-A571-68C46F4C87A2

Details:
10.0.17.146 - IP, can be any value (127.0.0.1, 192.168.1.1 etc.)
pid100 - can be pid100, pid121212 etc.

GUID - can be received from system

Note:
1.Find  and rename accordingly all folders (like 10.0.17.146_pid100)
with time of modification > 5 hour

2.The same task but don't use 'find' (modification time doesn't not
matter in this part)
