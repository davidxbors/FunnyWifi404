# FunnyWifi404

FunnyWifi404 is a simple and not very efficient Wifi password cracker.
It's meant to be used on OSX devices, where other alternatives don't really work or are a hassle.
By no means is this an efficient tool, meant to be used in professional environments.
** Use this tool only against networks whose owner's gave you explicit permission to use it. **

## Install

```bash
sudo ln -s /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport /usr/local/bin/airport
git clone https://github.com/davidxbors/FunnyWifi404.git
cd FunnyWifi404
chmod +x fw404-list
chmod +x fw404-dictionary
```

## Usage 

1. Pick your target using fw404-list.
1. Create a dictionary of passwords you want to use agains the target.
As this script is slow I'd recommend using a small and precise dictionary.
1. Run the script: `./fw404-dictionary INTERFACE SSID DICTIONARY`
