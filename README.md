# COME GET YOUR CORES

This is a repo of ai assisted coded, mixed sources based MiSTer FPGA and other platforms cores.
Those cores are made with JTFrame and haven't been submitted yet for review because the lack of additional hardware verification that for now is not feasible / possible.

The intent of those cores is still to be hardware verified and when it happens they get removed from here and become part of jtcores.

You can find the source for all those cores in a branch of jotego repo 'andrea-cores'
If some of those is not there, open an issue i have to probably recover it from another branch and move it there for organization purposes.

### Cores in this Repo


### Installation
You can either:
- [Download the repo specific ini file](https://github.com/TheJesusFish/Slop-Core/releases/tag/202607) and place it in your MiSTer's /media/fat directory. Update and Update_All will grab the cores the next time you run them.
- Add the below line to your `downloader.ini`. After doing that, Update and Update_All will grab the cores the next time you run them.

```ini
[asturur/Mister-cores]
db_url = https://raw.githubusercontent.com/asturur/Mister-cores/db/db.json.zip
```

![](https://i.imgur.com/gOLGQSJ.jpeg)
