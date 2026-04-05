## freebsd  

先調整時間 !!!
## tzsetup
CST

freebsd-update fetch
freebsd-update install

# sudo pkg update

pkg install nano
pkg install sudo

# pw user mod username -G wheel

/usr/local/etc/sudoers

root ALL=(ALL) ALL
calos ALL=(ALL) ALL #指定使用者
