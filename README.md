# Fix Os-Prober
To fix os-prober unable to detect or run do the following to fix:
 - go to `/etc/defaults/grub` then type at the bottom `GRUB_DISABLE_OS_PROBER = false`
# Things to do after running this script
## Edit sudo by using following commands:
`EDITOR=nano visudo`
## Uncomment the %wheel All=(ALL)ALL
