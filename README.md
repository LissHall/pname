# pname - Project Path Manager on MacOS & Linux
## Usage

```sh
Project Path Manager - Usage:
    pname add NAME [PATH]   # Add new path (uses current dir if PATH omitted)
    pname ls                # List all paths
    . pname cd NAME         # Change to specified path (prints path in quotes). 
                            # Note: Use `.` or `source`
    pname c NAME            # Copy quoted path to clipboard
    pname rm NAME           # Delete specific path record
    pname rm _all           # Delete ALL stored paths (requires confirmation)
```

## Download
```sh
cd Downloads
curl -o pname https://raw.githubusercontent.com/LissHall/pname/refs/heads/main/pname
```

## Install
```sh
sudo mv pname /usr/local/bin/pname
sudo chmod +x /usr/local/bin/pname
```
