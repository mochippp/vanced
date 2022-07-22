Firstly, you have to install Termux. To do this, you have to install [F-Droid](https://f-droid.org/).

After that, you have to run these commands:

```bash
termux-setup-storage
pkg update
pkg install wget nodejs-lts openjdk-17 -y
wget https://github.com/reisxd/revanced-builder/archive/refs/heads/cli.zip
unzip cli.zip
cd revanced-builder-cli
npm i
node .
```

After running `node .`, revanced-builder will install aapt2. 

You now can build ReVanced with revanced-builder!