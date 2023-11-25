<img src="https://github.com/KanojoOS/official_devices/blob/thirteen/banners/latest.png?raw=true">

# Kanojo OS

 Getting Started
---------------
To get started with the PixelOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/KanojoOS/manifesto.git -b thirteen
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
