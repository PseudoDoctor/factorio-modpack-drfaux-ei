# factorio-modpack-drfaux-ei
Factorio Modpack for Exotic Industries for the convenience of Dr Faux
# Factorio locations
## mods
```
➜ mods ls -1 | grep -v ".zip"
mod-list.json
mod-settings.dat
➜ mods 
```
### mod-list.json
```json
{
  "mods": 
  [
    {
      "name": "base",
      "enabled": true
    }, 
    {
      "name": "aai-loaders",
      "enabled": true
    },
    {
      "name": "yacp-ei-drfaux",
      "enabled": true
    },
    {
      "name": "YARM",
      "enabled": true
    }
  ]
}
```
## Windows
```
>cd $env:APPDATA\Factorio
C:\Users\onine\AppData\Roaming\Factorio
> ls | select Name,mode

Name                  Mode
----                  ----
config                d----
mods                  d----
saves                 d----
script-output         d----
temp                  d----
blueprint-storage.dat -a---
crop-cache.dat        -a---
factorio-current.log  -a---
factorio-previous.log -a---
player-data.json      -a---
```
## Mac
```log
~/Library/Application Support/factorio
    blueprint-storage.dat
    config
    crop-cache.dat
    factorio-current.log
    factorio-previous.log
    mods
    player-data.json
    saves
    temp
```
## Linux