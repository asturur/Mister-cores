# COME GET YOUR CORES

This is a repo of ai assisted coded, mixed sources based MiSTer FPGA and other platforms cores.
Those cores are made with JTFrame and haven't been submitted yet for review because the lack of additional hardware verification that for now is not feasible / possible.

The intent of those cores is still to be hardware verified and when it happens they get removed from here and become part of jtcores.

You can find the source for all those cores in a branch of jotego repo 'andrea-cores'
If some of those is not there, open an issue i have to probably recover it from another branch and move it there for organization purposes.

All cores are open source and the source is stored here:
https://github.com/jotego/jtcores/commits/andrea-cores
That branch contains either the exact source for this core or a newer version that is not published yet.

## Cores in this Repo

### JTPSPIKE
Covers
- Power Spikes / Super Volley '91
- Turbo Force
- AeroFighters / Sonic Wing ( in alternatives folder )
- Karate Blazers

### JTF1GRPR
Covers
- Formula 1 Grand Prix

### JTROUNDU
Covers
- Round Up 5

### JTSYSFL
Covers
- Final lap R
- Speed Racer

## Installation
- Add the below line to your `downloader.ini`. After doing that, Update and Update_All will grab the cores the next time you run them.

```ini
[asturur/Mister-cores]
db_url = https://raw.githubusercontent.com/asturur/Mister-cores/db/db.json.zip
```

This picture comes from TheJesusFish repo and i find it appropriate so i left it here

![](https://i.imgur.com/gOLGQSJ.jpeg)
