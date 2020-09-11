# About ecm2bc

**ecm2bc** is a shellscript that converts `ecm` and `ape` files into a `bin`/`cue` pair

# Dependencies

**ecm2bc** depends on these packages:
+ `ffmpeg`
+ `ecm` or `ecm-tools` (a package that provides `ecm-uncompress` command)

# Install

1. install the dependencies listed above

2. download `ecm2bc` file, or clone this repo if you want

3. move the file to any `$PATH` directory. e.g. `sudo mv ecm2bc /usr/local/bin`

# Run

1. extract the game and make sure the `ecm` and `ape` files are in the same directory

2. run `ecm2bc` command

3. give a name for the `bin`/`cue` files that will be generated **without extension** (the script will ask for this name)
