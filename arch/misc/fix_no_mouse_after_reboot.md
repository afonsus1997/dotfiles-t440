No mouse after lock/suspend
Add to /etc/default/grub
GRUB_CMDLINE_LINUX_DEFAULT= [...] psmouse.synaptics_intertouch=0