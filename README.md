# music

## Import to Spotify

https://nickwanders.com/projects/ng-spotify-importer/

## Export from Spotify

https://www.tunemymusic.com/transfer

## Triple J Net 50

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

https://rateyourmusic.com/release/comp/various-artists/kiss-my-wami-2003/

https://rateyourmusic.com/classifiers/Wami+Festival/

https://rwffmusic.blogspot.com/2018/12/20-years-ago-whistler-if-i-give-you.html

https://historyofaussiemusic.blogspot.com/2014/05/diana-ah-naid.html

https://www.discogs.com/release/5332628-Various-Beat-The-Drum-Triple-Js-Top-18-Music-Videos

https://www.discogs.com/label/291261-Triple-J?page=1

## Indie 2000

## Homebake

## Live at the wireless

https://www.discogs.com/release/2047711-Various-Triple-J-Five-Alive-Live-At-The-Wireless-Volume-Five
