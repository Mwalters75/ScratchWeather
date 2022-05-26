# Changelog
## January 30, 2022
- Created the project
- Added functionality to fetch weather information
- Added weather icons (SVG)
- Created local Git repository
- Added README.md
- Added LICENSE
- Pushed local Git repository to GitHub
## January 31, 2022
- Added CHANGELOG.md
- Came to a conclusion that ScratchWeather will be worked on a local Git repository, then pushed to GitHub
- Added refresh keyboard shortcut: <kbd>Ctrl</kbd> + <kbd>Enter</kbd>
- Added thumbnail
- ScractchWeather will be in private beta until further notice
- Added tempature information (in metric)
- Patched so-called STE
## February 1, 2022
- Upgraded ScratchWeather to widescreen
- Updated costumes to fit the new widescreen format
- Added console logging
- Fixed bug where sprite from before shows when project is restarted
- Figured out that the bug was caused by a wrong broadcast
- Changed hat block, because the bug persisted
- Putting in a Pen Slider Engine to show progress on re-compiling the JSON
- Upgraded Pen Slider Engine to progress bar
## February 2, 2022
- Upgraded the <kbd>Ctrl</kbd> key to a TurboWarp Key
## Feburuary 3, 2022
- Made new slider
- Removed slider border
- Added automatic refresh (300 seconds, or 5 minutes to avoid HTTP 429 errors)
## Feburuary 7, 2022
- Added a backdrop fade out effect when refreshing, and a fade in effect when loaded
- Fixed the maximum x position to be met (or exceeded) to make a line break from 220 (for 480x360 display) to 300 (640x360)
- Added a new TurboWarp setting: Remove Fencing (did this so sprites can go over the x and y position limits)
## Feburuary 10, 2022
- Removed all CloudLink blocks
- Replaced CloudLink blocks to TurboFoolishness for opening ScratchWeather on TurboWarp Desktop
## February 11, 2022
- Made tempature more accurate by rounding
## February 16, 2022
- Moved repository to a GitHub org
- Changed upstream URL in local git
## February 17, 2022
- Paid attribution to makers of sprites in ScratchWeather. The sprites without comments means that the sprites was made by the ScratchWeather team
- Broadcast loading while "extract and rewrite" is being run
## February 23, 2022
- Made the STE up-to-date by manually getting the sprite, because of new changes
- Removed stage size measurer
## February 28, 2022
- Added automatic location finding based on user's IP address (2 more APIs, 3 in total)
- Made a variable called API key for better management of the API key
## March 3, 2022
- Upgraded all old fetcher blocks to (get [] using [GET v])
## March 7, 2022
- Renamed "extract and rewrite" to "download and rewrite"
- Download EVERYTHING for compact usage, and less requests to the server, avoiding HTTP 429 errors
> At this time, ScratchWeather broke, due to a single comma. It can read the API answer, but not without TurboFoolishness balking at a single comma.

> All changes made on this day was scrapped, due to the comma bug.
## March 10, 2022
> No testing was done during the three-day break. Today, testing and developing went back on track, and the comma bug has been fixed. The bug may have been caused by the OpenWeatherMap API, but, originally, we thought it was the new features making the bugs, thus making that the reason why everything from March 7, which basically are new features and additions to existing features.
## March 16, 2022
- Remade changes from March 7, 2022
## April 19, 2022
> On this day, ScratchWeather became from closed beta, to public beta.
- Uploaded the ScratchWeather `.sb3`
> At this time, ScratchWeather's development went back on track, after over a month of development breaks.

> ScratchWeather was uploaded to GitHub for two reasons:
> 
> 1. To use GitHub as a backup for ScratchWeather
> 
> 2. Because I didn't mean to be greedy.
## May 26, 2022
- Performed extensive block cleanup
- Size reduced by 40 KB
- Loads more faster
> Making it load faster required some blocks to be deleted.
- Removed API key from `.sb3` and deactivated/deleted the key.
- You are now required to have a OpenWeatherMap API key to use ScratchWeather. It's free, so it shouldn't be a big deal.
