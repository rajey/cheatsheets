# Linux commands cheatsheet

### rsync with a non-standard SSH Port

`rsync -avz -e "ssh -p $portNumber" user@remoteip:/path/to/files/ /local/path/`
