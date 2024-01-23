# Kanojo OS

 Getting Started
---------------
To get started with the PixelOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use command:

```bash
repo init --depth=1 --no-repo-verify -u https://github.com/PixelOS-Fourteen/manifest.git -b fourteen-qpr1 --git-lfs -g default,-mips,-darwin,-notdefault
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch kanojo_devicecodename-buildtype
```

Start compilation

```bash
make kanojo
```
