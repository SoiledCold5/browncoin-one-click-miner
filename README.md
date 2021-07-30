# Browncoin One-Click Miner

This program will create a Browncoin wallet that only you have access to. Encrypt your wallet with a password that you will not forget. It will then create the Verthash datafile and immediately begin mining Browncoin. You will receive payouts in Browncoin to your built-in Browncoin wallet from the pool selected in Settings. 

This is a redevelopment of Vertcoin's [One Click Miner](https://github.com/vertcoin-project/one-click-miner).

This software is available for Windows and Linux.

## FAQ

### Which GPUs are supported?

Please refer to this list of [supported hardware.](https://github.com/CryptoGraphics/VerthashMiner#supported-hardware)

### I have an error message that reads 'Failure to configure'

You may need to add an exclusion to your antivirus / Windows Defender.

### My GPU is supported but an error messages reads 'no compatible GPUs'

Update your GPU drivers to the latest version.

## Building

The GUI of this MVP is based on [Wails](https://wails.app) and [Go](https://golang.org/).

Install the Wails [prerequisites](https://wails.app/home.html#prerequisites) for your platform, and then run:

```bash
go get github.com/wailsapp/wails/cmd/wails
```

Then clone this repository, and inside its main folder, execute:

```bash
wails build
```

## Donations

If you want to support the further development of the One Click Miner, feel free to donate Vertcoin (VTC) to [Vmnbtn5nnNbs1otuYa2LGBtEyFuarFY1f8](https://insight.vertcoin.org/address/Vmnbtn5nnNbs1otuYa2LGBtEyFuarFY1f8).
