# CMD Patch
An Android Linux Kernel command line patch tool using Magisk's magiskboot binary.

# Usage
`cmdpatch <CMDLINE ARGUMENTS>`

Example: `cmdpatch scsi_mod.use_blk_mq=1`

This patches the boot image to use multiqueue by default for SCSI devices. After this finishes, reboot to apply the changes.
