# my-grub-settings-ryzen-nvidia
Grub settings I use in arch for ryzen / NVIDIA setup


Please note that these settings worked for me and may not work for you, to finalize changes run sudo grub-mkconfig -o /boot/grub/grub.cfg.  I have noticed a few issues with suspend messing with video playback but will update this repo with every change I make to my system.  Hope this helps you and use at your own risk always keep a recovery drive handy in case you need to chroot! :)


Also noticed editing /etc/fstab and changing norelatime to noatime also seemed to help as did updating the motherboard firmware(something that seems to fix 99% of problems I have haha)
