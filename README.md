# NekoFrue Kernel
The NekoFrue kernel is an open-source Linux alternative (sort of)

# Prerequisites
- `flex`
- `make`
- An hour or two of your time and sanity

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
