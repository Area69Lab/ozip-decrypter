# Ozip Decrypting online made easy #

## What this is ##

This is an easy way to decrypt Ozip (Firmware of oppo/realme) to a TWRP Flashable Zip. This works with GitHub actions, thank GitHub not me :)

## How to use ##

Here are some useful notes to using this tool brewed with black magic xD !

1. Fork the repo
1. Set the variables, as listed below:

    - `FIRMWARE_LINK` : Direct Link to ozip (can be found in realme/oppo website, or yours. HTTP/HTTPS, FTP, SFTP, BitTorrent and Metalink are supported)
    - `FIRMWARE_NAME` : The Name of Ozip (i.e CPH1861EX_11_OTA_0500_all_fLuS0Ipoe93t.ozip)
    - `FIRMWARE_ZIP_NAME`: The Name of zip to be created
1. SFTP is used here to upload the zip to SourceForge. You can modify upload section as per your needs. But to use SourceForge (default), go to the `settings` tab of the repo and create the encrypted secrets listed below:

    - `SFUSER`: SourceForge username
    - `SFPASS`: SourceForge password
    - `SFDIR`: SourceForge project directory (i.e `/home/frs/project/<PROJECT_NAME>/<FOLDER_NAME>/`)

    More about SFTP file uploading to SourceForge can be found [here](https://sourceforge.net/p/forge/documentation/Release%20Files%20for%20Download/#sftp). And the docs about encrypted secrets are [here](https://docs.github.com/en/actions/reference/encrypted-secrets)
1. Go to the `actions` tab and enable workflows.
1. Star the repo, go to actions tab again, the workflow must have started. Now let Magic Work xD

## Credits ##

**Thanks to the people who helped me**

- Script Made by [***Aryan Sinha***](https://github.com/techyminati)
- Huge help from [***ElytrA8***](https://github.com/Elytra8)
- Docs & workflow updated by [***chankruze***](https://github.com/chankruze)

Enjoy Decrypting Ozip Online :)

©Area69Lab
