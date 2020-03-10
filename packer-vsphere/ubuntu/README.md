

```
root@ubuntu:~/huan# packer build iso.json
vsphere-iso: output will be in this color.

==> vsphere-iso: Creating VM...
==> vsphere-iso: Customizing hardware...
==> vsphere-iso: Mounting ISO images...
==> vsphere-iso: Creating floppy disk...
    vsphere-iso: Copying files flatly from floppy_files
    vsphere-iso: Copying file: floppy_files/preseed.cfg
    vsphere-iso: Done copying files from floppy_files
    vsphere-iso: Collecting paths from floppy_dirs
    vsphere-iso: Resulting paths from floppy_dirs : []
    vsphere-iso: Done copying paths from floppy_dirs
==> vsphere-iso: Uploading created floppy image
==> vsphere-iso: Adding generated Floppy...
==> vsphere-iso: Set boot order temporary...
==> vsphere-iso: Power on VM...
==> vsphere-iso: Waiting 10s for boot...
==> vsphere-iso: Typing boot command...
==> vsphere-iso: Waiting for IP...
==> vsphere-iso: IP address: 10.100.100.64
==> vsphere-iso: Using ssh communicator to connect: 10.100.100.64
==> vsphere-iso: Waiting for SSH to become available...
==> vsphere-iso: Connected to SSH!
==> vsphere-iso: Provisioning with shell script: /tmp/packer-shell089458886
    vsphere-iso: bin
    vsphere-iso: boot
    vsphere-iso: dev
    vsphere-iso: etc
    vsphere-iso: home
    vsphere-iso: initrd.img
    vsphere-iso: lib
    vsphere-iso: lib64
    vsphere-iso: lost+found
    vsphere-iso: media
    vsphere-iso: mnt
    vsphere-iso: opt
    vsphere-iso: proc
    vsphere-iso: root
    vsphere-iso: run
    vsphere-iso: sbin
    vsphere-iso: srv
    vsphere-iso: sys
    vsphere-iso: tmp
    vsphere-iso: usr
    vsphere-iso: var
    vsphere-iso: vmlinuz
==> vsphere-iso: Shut down VM...
==> vsphere-iso: Deleting Floppy drives...
==> vsphere-iso: Deleting Floppy image...
==> vsphere-iso: Eject CD-ROM drives...
==> vsphere-iso: Convert VM into template...
==> vsphere-iso: Clear boot order...
Build 'vsphere-iso' finished.

==> Builds finished. The artifacts of successful builds are:
--> vsphere-iso: huan-iso-test-1
```
