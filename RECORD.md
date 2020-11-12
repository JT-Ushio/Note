---
`sshfs -o uid=$UID,gid=$GROUPS taoji@10.141.209.6:/home/taoji/data/ data` failed
fuse: bad mount point `data`: Transport endpoint is not connected
**Solution**:  `fusermount -uz data`

---
[How to add padding mask to nn.TransformerEncoder module?](http://jalammar.github.io/illustrated-transformer/)
[torch.nn.TransformerEncoder.forward-Shape](https://stackoverflow.com/questions/62399243/transformerencoder-with-a-padding-mask)

---
`pip install -i https://pypi.tuna.tsinghua.edu.cn/simple transformers --user --proxy=http://10.176.51.11:3128`

---
How to customize your own LR schedule.