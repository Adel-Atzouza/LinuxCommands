# LinuxCommands
A repository where I save useful Linux commands that I have used.


## Filesystems
To fix ntfs disk errors that prevent it from mounting I have used this command.
*Where /XXX/XXXX was /dev/sda4*
```bash
sudo ntfsfix -d /XXX/XXXX
```
To fix ext4 disk errors that prevent it from mounting I have used this command.
*Where /XXX/XXXX was /dev/sda4*
```bash
sudo fsck -y /XXX/XXXX
```
