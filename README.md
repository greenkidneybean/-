# 🍓🗄️🍓
Raspberry Pi OMV NAS

## Resources
- [Video guide for headless Pi setup](https://www.youtube.com/watch?v=hCxT0A-5_9k&t=580s)
- [YouTube video to make cheap Pi NAS](https://www.youtube.com/watch?v=KKpPgwa_Fys)
- [Create Mac Photos sparse image on ext4 HD](https://discussions.apple.com/thread/8030554)
- [Mounting and unmounting drives on unix](https://linuxize.com/post/how-to-mount-and-unmount-file-systems-in-linux/)

## STATUS: moving data from /ChambersPhotoHome to /Magnolia, probably need to reformat drive for OMV
- use existing ext4 format for the SSD
- create 1TB sparse image for the photos library (will expand as data added)
- trying to rename the disk device name
  - Device: ChambersPhoto
  - Mount point: /ChambersPhotoHome (this has all the data)
  - there is also /Magnolia

## Build Guide:
- Download Raspberry Pi imager
- 

## Mounting drive on unix
- `mount -t ext4` to list the ext4 drives available
- `sudo mount /dev/sda1 /media` to mount the disk to the root media directory
