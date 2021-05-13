# VLPP Pack
Create and automatically copy Vita Lua Player Plus VPK's to a PSVita in linux


# How to use
### Dependencies
You will need to install ``zip`` and ``vitasdk``.

### Installing
To install run the following commands.
```
git clone https://github.com/raxracks/vlpp-pack
cd vlpp-pack
chmod +x vlpp-pack
sudo mv vlpp-pack /bin/
```

You can now delete the folder if you wish.

### Packaging
First plug in your PSVita, launch VitaShell, and connect with USB.

Open a terminal into the folder where the package files are contained (eboot.bin, sce_sys), and run the following command.
```
vlpp-pack
```
If it works properly, the VPK will be created, the PSVita will be detected, and mounted, the files will be copied, and then the PSVita will be unmounted.

The first time you run the command it will ask you to choose a 9 letter ID and an application name, the ID must be 9 letters or you will have an error when installing the package in VitaShell.
