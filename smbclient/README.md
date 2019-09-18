# Description

smbclient based on Alpine image.

## Running the command

```
docker run --rm -v ./data:/data codebreaker1/smbclient -U <domain\\username>%<password> //<address of samba server>/<share name>/ -D <subdirectory>/ -c "get <filename>"
```
