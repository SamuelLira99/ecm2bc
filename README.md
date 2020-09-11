# About ecm2bc

**ecm2bc** is a shellscript that converts `ecm` and `ape` files into a `bin`/`cue` pair

It was designed specifically for **PS1 games** to be able to work with [cue2pops](https://github.com/makefu/cue2pops-linux) , but can be used for other purposes that require single bin/cue pair

Even if the game has muliple tracks, the resulting files will be exactly **1 bin** and **1 cue** file. In this case the generated bin file will contain all tracks

# Dependencies

**ecm2bc** depends on the following packages (the arch-like method will install them automaticaly):
+ `ffmpeg`
+ `ecm` or `ecm-tools`

# Install

### Arch-like distros

1. download files `PKGBUILD` and `ecm2bc.install` to same directory, or clone this repo if you want

2. open the terminal on the directory the files were downloaded to

3. run `makepkg -si`

### Other distros

1. install the dependencies listed above

2. download `ecm2bc` file, or clone this repo if you want

3. move the file to any `$PATH` directory. e.g. `sudo mv ecm2bc /usr/local/bin`

# Run

1. extract the game and make sure the `ecm` and `ape` files are in the same directory

2. run `ecm2bc` command

3. give a name for the `bin`/`cue` files that will be generated **without extension** (the script will ask for this name)
