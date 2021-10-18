# Hearthstone-Mercenaries-game-bot
The main idea of  the bot is to automatically pass the levels and assemble components, 
simultaneously pumping all your mercenaries level 1 to 30 (so far, then to add)
So how does it work?
in fact, everything is based on the fact that the bot collects a team of 3 of your heroes of level 30, 
and then throws 1 level there, and since for pumping the unit does not have to participate in the battle, 
the bot just passes the location time and time again and shakes the rest of your mercenaries to level 30.

In plans
1. Finish Project
2. Add mode selection - collecting fragments/pumping heroes
3. write a graphical interface for this whole case
4. It is possible to expand the functionality originally conceived.

<h1 align="center">Specification, Settings.ini file:</h1>
<img align="right" src="https://user-images.githubusercontent.com/68296704/137646221-10164e4f-d2b6-428d-b854-7ffeb715ef2e.png"></img>


```diff
[BotSettings]
monitor=1 
bot_speed=0.5 
+0.1-the fastest mode , 5-the slowest (not recomending do faster then 0.5) 
[Hero1]
number = 1
colour = Red
[Hero2]
number = 2
colour = Green
[Hero3]
number = 3
colour = Blue
+3 main heroes that you will use for pumping other ones.List of heroes by numbers you can see in in HeroesList.txt

[NumberOfPages]
Red = 1
Green = 2
Blue = 2

[Resolution]
Monitor Resolution = 2560*1440
+could be 2560*1440 or 1920*1080

```

<br>
<br>
<br>
<div align="left">
HeroList<br>
1 - Cariel Roame /Кариэль Роум<br>
2 -Tyrande / Тиранда<br>
3 -Milhous Manostorm / Милхаус маношторм<br>
</div>

For contacts andrey115516@gmail.com



![Psl3Wv3IZgs](https://user-images.githubusercontent.com/68296704/137604260-9981e52b-0fd8-469c-8b36-d5f1dfa9e8a6.jpg)
