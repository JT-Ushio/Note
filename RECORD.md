---
`sshfs -o uid=$UID,gid=$GROUPS taoji@10.141.209.6:/home/taoji/data/ data` failed
fuse: bad mount point `data`: Transport endpoint is not connected
**Solution**:  `fusermount -uz data`

---