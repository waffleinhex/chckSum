# chckSum
chckSum is an easy tool to check whether the checksum of a downloaded file is the same as the checksum provided by the vendor.

>WARNING!
>chckSum currently can run any code on your computer, DO NOT copy any ./chckSum commands from online
>Usage explained in [Running](#Running)

# Running
> [!IMPORTANT]
> Make sure to make the file executable before attempting to run. To do this, run ```chmod +x chckSum``` in the directory chckSum is stored.

To run, simply type `./chckSum <checksum type> <input file> <original checksum>` in the directory the script is stored.

# Installation
To install, just download the file, if you want to run it system-wide then enter the folder with chckSum and do this command:  

> [!IMPORTANT]
> sudo is required to run this command (if /usr/bin's permissions are set to unallow user writing to it)

```
sudo cp ./chckSum /usr/bin/
```
After that, chckSum will be installed system-wide.

# Setting an alias
If you, for some reason, needed to store this file elsewhere, you can add chckSum as an alias in your ~/.zshrc or ~/.bashrc file.

Lets say you stored it in your documents folder. To set an alias for it, you would run the command:
```
echo "alias chcksum="sh ~/Documents/chckSum" >> ~/.zshrc
```
or
```
echo "alias chcksum="sh ~/Documents/chckSum" >> ~/.bashrc
```
depending on which shell you use.
If you use a different shell, you know how to set an alias.
