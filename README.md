# Music Stuff

## How to import a .CSV to Spotify

https://nickwanders.com/projects/ng-spotify-importer/

## Export your music library from Spotify

https://www.tunemymusic.com/transfer

## Triple J Net 50 - 1999-2003
- [List of all votable songs from Triple J's Net 50 show](https://github.com/SpitFire-666/music/blob/main/Triple%20J%20Net%2050%201999-2003.txt)
- Originally from [this list](https://gist.github.com/initials/86e466ee84151fc930234e99564270ac), but I fixed it up by removing duplicates, formatting all to Artist - Title
- I also imported the tracks to a [Spotify Playlist](https://open.spotify.com/playlist/3Il2U91erdkbKLNVqQTyTU)
- Example way back machine link to a Net 50 voting page
https://web.archive.org/web/19981205010727/http://www.abc.net.au/triplej/net50/vote.htm


## Rage Again

https://rageagain.com/#/home

1. Scrape links

2. Gather json URLs, eg https://rageagain.pjgalbraith.workers.dev/api/data/1998/01/03.json
3. Use PowerShell to dump the .json into CSV
```powershell
(iwr "https://rageagain.pjgalbraith.workers.dev/api/data/1998/01/03.json" | ConvertFrom-Json).tracks | Export-Csv -NoClobber -Append -Path ~\desktop\rage1998.csv
``` 
https://rageagain.com/#/episode/2022/02/20_night/1

https://rageagain.pjgalbraith.workers.dev/api/data/2022/02/20_night.json

https://rageagain.pjgalbraith.workers.dev/api/data/1999/12/25_night.json

https://rageagain.com/#/episode/1999/12/25/1

##  Others



https://rwffmusic.blogspot.com/2018/12/20-years-ago-whistler-if-i-give-you.html

https://historyofaussiemusic.blogspot.com/2014/05/diana-ah-naid.html

https://www.discogs.com/release/5332628-Various-Beat-The-Drum-Triple-Js-Top-18-Music-Videos

https://www.discogs.com/label/291261-Triple-J?page=1

## Kiss my WAMI

https://www.discogs.com/release/9621833-Various-Kiss-My-WAMi-2002


https://rateyourmusic.com/release/comp/various-artists/kiss-my-wami-2003/

https://rateyourmusic.com/classifiers/Wami+Festival/

https://www.discogs.com/release/10495116-Various-Kiss-My-Wami-2001
https://www.discogs.com/release/9755426-Various-Kiss-My-Wami-2000
https://www.discogs.com/release/14759254-Various-Kiss-My-Wami-99
https://www.discogs.com/release/14091412-Various-Kiss-My-WAMi-1997


https://www.discogs.com/label/1264993-Kiss-My-WAMi?page=1

https://www.discogs.com/release/12204313-Various-Kiss-My-Wami-98

## Indie 2000

## Triple J Unearthed CDs

### Unearthed 1

![unerthcd1sm](https://github.com/SpitFire-666/music/assets/38451588/537ca9b4-7b27-46fe-bbcd-a160242ed42d)

ODE TO A GOLDFISH - UNDRESS ME (Lismore)

GRINSPOON - SICKFEST (Lismore)

MILHOUSE - OODLES (Bendigo)

STEPHEN SAXTON - PENNY DROPS (Bendigo)

STONEHENGE - OUR WAY (Townsville)

GRAVEL SAMWIDGE - DRINKING WITH A DEAD MAN (Townsville)

RAVEN - ANGERWUY (Alice Springs)

DROWN - AND (Dubbo/Coonabarabran)


![unert2cdsm](https://github.com/SpitFire-666/music/assets/38451588/290adfcb-9f9d-4d32-a168-09a38a76c2ad)

PORCELEIN - GLO (Broken Hill)

SWELL - DISDAIN (Broken Hill)

EVOL - RUBBING ME (Wollongong)

WET PHIBIANS - ONLY (Albury/Wodonga)

HUMBUG - WAX (Albury/Wodonga)

COMMUNION - DEAD RAIN (Gold Coast)

PLANET CACTUS - OUT OF MY HEAD (Gold Coast)

THE EARLY HOURS - I'M DRAINED (Kalgoorlie/Boulder)


## Homebake

## Live at the wireless

https://www.discogs.com/release/2047711-Various-Triple-J-Five-Alive-Live-At-The-Wireless-Volume-Five
