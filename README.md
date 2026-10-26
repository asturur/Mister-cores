# COME GET YOUR CORES

This is a repo of ai assisted coded, mixed sources based MiSTer FPGA and other platforms cores.
Those cores are made with JTFrame and haven't been submitted yet for review because the lack of additional hardware verification that for now is not feasible / possible.

Those cores are finished and not more in development, are not betas.
they can get occasional updates when jtframe is updated or a chip is improved.

There may be bugs like any other software, and i didn't play each game and variant from start to end.

What should always work via jtframe conventions is:

- Direct video and correct pixel clock
- CRT support with Flip for vertical games
- Controls mapping with correct named buttons
- Analog controls were appropriate

The intent of those cores is still to be hardware verified and when it happens they get removed from here and become part of jtcores.

Also those cores are multiplatform you can find the version for
- mister
- sidi
- mist
- sidi128
- analogue pocket

*When the core fits*.

You can find the source for all those cores in a branch of jotego repo 'andrea-cores'
If some of those is not there, it is somewhere else public for sure, just open an issue i have to probably recover it from another branch and move it there for organization purposes. [branch](https://github.com/jotego/jtcores/commits/andrea-cores)
That branch contains either the exact source for this core or a newer version that is not published yet.

## Cores in this Repo

### JTSVOLLE
Covers
- Super Volley
- Rabio Lepus / Rabbit Punch ( not included to do not clash with a duplicate )

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

## Funding

If you considered sponsor this project i prefer you sponsor [jotego](https://github.com/jotego/jtcores) that is the source of the modules and framework for those cores to be possible.
If you are already a sponsor of jotego and you still want to sponsor the efforts, consider sponsoring [Zaparoo](https://github.com/ZaparooProject) that is what made me start developing in this space.
Sponsoring those projects in the long term is more beneficial in my opinion.

If you really want to give me something as a token of gratitude i have a sponsor button in my profile too.



This picture comes from TheJesusFish repo and i find it appropriate so i left it here

![](https://i.imgur.com/gOLGQSJ.jpeg)
