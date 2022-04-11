# Asphalt9win
Command line arguments  
| **Argumnent**     | **Short**         | **Description**  |
| ------------- |:-------------:|:-----|
| -task         |-t | Single task name |
|-repeat        |-r | Number of repetitions of a single task |
|-param         |-p | String parameter for a single task | 
|-cars          |-c | Cars preset for a single task like Hunt |
|-map           |-m | Forced navigation setting |
|-minTime       |   | Driving no better than a set time  (Race & Hunt only) |
|-maxTime       |   | Driving no worse than the set time (Race & Hunt only) |
|-file          |-f | Path to the file with multiple task |
|-delay         |-d | Pre-start pause in seconds (default = 0) |
|-windowName    |-n | A9 window name (default «Asphalt 9: Legends») |
|-windowX       |-x | Set the window to the specified X coordinate (default = -7) |
|-windowY       |-y | Set the window to the specified X coordinate (default = 0) |
|-windowWidth   |-w | Set the specified window width (default = 1056) |
|-windowHeight  |-h | Set the specified window height (default = 521) |

**Examples:**  
BCompilerDebug.exe -t MP1 -r 100
BCompilerDebug.exe -t MP2 -r 100
BCompilerDebug.exe -t Hunt -r 5 -cars B4 -map "The Caribbean: ISLET RACE"
BCompilerDebug.exe -t NavStat
BCompilerDebug.exe -t ShowStats
BCompilerDebug.exe -f EveryDay.txt
EveryDay.txt
```javascript
//daily tasks
DailyEvents 6 Hunt cars:C4
//Hunt 3 cars:C4 map:Buenos_Aires:_CROSSTOWN event:HUNT_ELVA
//MP1Downgrade 10 silver
//MP2 15
MP1 25
```
