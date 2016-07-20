## Map: upull_coop
#####Insurgency co-op checkpoint map

### Inspiration:
![alt text](https://i.imgur.com/9vBCxBT.jpg "Map inspiration 01")

![alt text](https://i.imgur.com/VOYzWhU.jpg "Map inspiration 02")
Source: https://www.google.com/maps/@39.7377176,-104.7727995,184m/data=!3m1!1e3

### Progress:
![alt text](https://i.imgur.com/mgXV5aD.png "Map Progress 01")

![alt text](https://i.imgur.com/YU4FHzq.png "Map Progress 02")

![alt text](https://i.imgur.com/w4DrOaN.png "Map Progress 03")

### Create bot navigation file:
> Type nav_edit 1 in console

> Look down at the ground in front of you and type nav_mark_walkable

> Type nav_generate in console

![alt text](https://i.imgur.com/PJ5cg7d.png "Map Progress 04")

![alt text](https://i.imgur.com/F1bvoqa.png "Map Progress 05")

### Current map preview:
![alt text](http://i.imgur.com/5p8Mnph.jpg "Map Preview 01")

![alt text](https://i.imgur.com/TPaDgEa.png "Map Progress 06")

### Finding errors in console:
> Failed finding guard spots for CP 0, Team 3

> Failed finding guard spots for CP 1, Team 3

![alt text](https://i.imgur.com/EzoQL0Q.png "Console Errors 01")

![alt text](https://i.imgur.com/f9TCjG3.png "Console Errors 02")

### Solution:
> Move "info_player_start" outside of an spawnzone and then run "nav_generate" again

> Make sure all ins_spawnpoints are linked to a spawn zone

> In the object properties window under the "flags" tag, check the box "controlled by a spawn zone"

> Also look into using some blockzones to control the flow of the game

![alt text](https://i.imgur.com/0lIUqBy.png "Map Progress 07")

![alt text](https://i.imgur.com/eZPmhDI.png "Map Progress 08")

![alt text](https://i.imgur.com/daMhZcb.png "Map Progress 09")

![alt text](https://i.imgur.com/xVShj9B.png "Map Progress 10")

![alt text](https://i.imgur.com/4WdTZGG.png "Map Progress 11")

![alt text](https://i.imgur.com/iBE8uPx.png "Map Progress 12")

![alt text](https://i.imgur.com/6Gn3AkX.png "Map Progress 13")

![alt text](https://i.imgur.com/huOyU1L.png "Map Progress 14")

### Checking in game texture and placement errors:
![alt text](https://i.imgur.com/f0baF11.jpg "Map Preview 02")

![alt text](https://i.imgur.com/oPpgw5m.jpg "Map Progress 15")

### Current map preview:
![alt text](https://i.imgur.com/cBLUZWX.jpg "Map Preview 03")

![alt text](https://i.imgur.com/BpJulDz.jpg "Map Preview 04")

![alt text](https://i.imgur.com/FlUAk6h.png "Map Progress 16")
