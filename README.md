# Telegram Folder Channels List Exporter

The program exports list of channels and groups for each Telegram folder. It does
not export messages.

What is chat folders: https://telegram.org/blog/folders

## Config file

Create "var/config.yml" file with a following content

```
tg:
  app_id: ...
  app_hash: ...
```

## Installation and usage

```
git clone https://github.com/lorien/tgfolder_export
cd tgfolder_export
make init
source .env/bin/activate
# create config file, see above
./export.py > export.json
```
