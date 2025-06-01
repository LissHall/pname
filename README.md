# pname - Project Path Manager on MacOS & Linux
## Usage

```sh
  pname add NAME [PATH]   # Add new path (uses current dir if PATH omitted)
  pname ls                # List all paths
  pname cd NAME           # Change to specified path (prints path in quotes)
  pname rm NAME           # Delete specific path record
  pname rm _all           # Delete ALL stored paths (requires confirmation)
```

## Install
```sh
sudo mv pname /usr/local/bin/pname
sudo chmod +x /usr/local/bin/pname
```
