# NekoFrue Kernel
The NekoFrue kernel is an open-source Linux alternative (sort of)
(.config, Makefile, etc. are made by NekoMimi#7225)
![Untitled132_20220821172356](https://user-images.githubusercontent.com/88291291/185815668-ca0d3d51-6dce-47e9-a864-f917b0dbf547.png)
# Prerequisites
(mainly for Debian, you'll need these:)
- `flex`
- `make`
- An hour or two of your time and sanity
- `libncurses-dev` 
- `bison`
- `libssl-dev`
- `libelf-dev` 
- `gzip` 
- `lzo`
- `fakeroot`
(once again, these are prerequisites for Debian, for other distros it might be different! You'll have to figure it out on your own.)

# How to Do  It
- First, what you'll need to do is download the .zip of the custom kernel config here **(in Releases tab)**, and also download the current kernel from https://kernel.org
- Now,  extract the zip of the NekoFrue kernel stuff, and extract the Linux kernel as well (preferably in a directory like `~/kernel`
- Replace the `Makefile` and `.config` with the ones from the NekoFrue folder

Now the hard part,

- `cd` to the kernel directory
- Run `make`
Once it's done compiling,
- Run `make modules_install` as root (or sudo)
- Run `make install` as root (or sudo)

# Support

-Is available in our Discord server: https://discord.gg/qRysc6bVRv
