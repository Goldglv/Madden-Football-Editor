## John Madden Football Roster Editor for Genesis/Super Nintendo

Latest release: https://github.com/Goldglv/John-Madden-Football-Roster-Editor/releases

This app will enable you to update Rosters for the following Systems/Madden Football Games:

## **Sega Genesis/Megadrive**
- John Madden Football ('91) 
- John Madden Football '92 
- John Madden Football '93 
- John Madden Football '93 Championship Edition 
- Madden NFL '94 
- Madden NFL '98 (Will update player numbers but not player names)

## **Super Nintendo**
- Madden NFL '94

This also works with the Madden ‘93 ROM for Genesis that was updated to include the Jaguars, Panthers, Ravens and Texans. Please contact me for further details in obtaining this ROM.  The original ROM's don't have these teams in the game so there's no way to import them from Excel.

The Editor will automatically remove the checksum for all games listed above so you should have no issue running the game after you modify the ROM.

How to Use Double click on the exe and choose any Madden game listed above and the Editor will open, showing all of the player data for each team. Choose a team you want to edit by selecting it in the dropdown on the upper left. Editor converts ratings from 0-99 to 0-15 so the game can read it. After you're done changing the player data, make sure to click SAVE, the editor is designed to update ONE TEAM AT A TIME (unless you use the Import From Excel feature mentioned below). If you edit one team and go on to another without saving, your changes will be lost.

If you want to use the 'Import from Excel' feature you need to make sure of the following:

I based my editor off the ratings from https://maddenratings.weebly.com/madden-nfl-24.html You can download all of the rosters for each team here. As of 12/24, these spreadsheets are working with my editor because the column headers match up. You must make sure that the following column headers are included in whatever spreadsheet you import from. You can have additional column headers, I just ignore them.

I've included the maddenNFL24FullPlayerRatings.xlsx file with all 32 teams and all player ratings with the correct column headings mentioned below.  These ratings were from the beginning of the 24 season so they may not be completely up to date but if you import this file, every team in the ROM can be updated within a few seconds.  

New for v3.0 and onward, I've added the ability to update as many teams as you want at one time, you can do 1, 3 or all 32 teams with one click of the Import From Excel button.  My program will run through each team you have listed and will update as many teams as you have listed in your spreadsheet.  This makes this process even easier than with previous versions.  If it comes to a team listed in your spreadsheet that's not in the game, you will get a message.  I've added code for this to still work if you have the Titans or the Commanders in your spreadsheet, it will just update player data for the Oilers and Redskins respectively.

- Agility
- Awareness
- Break Tackle
- Carrying
- Catching
- Hit Ability
- Jersey Number 
- Kick Power
- Kick Accuracy
- Man Coverage
- Overall Rating
- Pass Block
- Position
- Pursuit
- Run Block
- Speed
- Tackle
- Team
- Throw Accuracy Middle
- Throw On The Run
- Throw Power
- Weight

Again, the column headers in your spreadsheet MUST MATCH EXACTLY with what's above.

Also, for positions (which as of 12/24 are exactly what I'm looking for in my editor) YOU MUST MAKE SURE THEY MATCH EXACTLY below (PR/KR are not included in the spreadsheets so you can either update them manually within the editor or add them to your spreadsheet after you've downloaded them):

C/CB/DT/FB/FS/HB/K/KR/LE/LG/LOLB/LT/MLB/P/PR/QB/RE/RG/ROLB/RT/SS/TE/WR

## **Editor/Spreadsheet/Positon Name**

- QB - QB - Quarterback
- HB - HB - Halfback
- FB - FB - Fullback
- KR - KR - Kick Returner
- PR - PR - Punt Returner
- LT - LT - Left Tackle
- LG - LG - Left Guard
- C - C - Center
- RG - RG - RIght Guard
- RT - RT - Right Tackle
- WR - WR - Wide Receiver
- TE - TE - Tight End
- K - K - Kicker
- P - P - Punter
- LDE - LE - Left Defensive End
- LDT - DT - Left Defensive Tackle
- RDT - DT - Right Defensive Tackle
- RDE - RE - Right Defensive End
- LOLB - LOLB - Left Outside Linebacker
- LILB - MLB - Left Inside Linebacker
- RILB - MLB - Right Inside Linebacker
- ROLB - ROLB - Right Outside Linebacker
- LCB1 - CB - Left Cornerback 1
- RCB1 - CB - Right Cornerback 1
- LCB2 - CB - Left Cornerback 2
- RCB2 - CB - Right Cornerback 2
- SS - SS - Strong Saftey
- FS - FS - Free Safety


All of these columns and positions are included in the spreadsheets from the link I mentioned above so it would be much easier to use those. One IMPORTANT note, within the editor, for example, you have QB1 and QB2. I thought about manually updating all the positions in the spreadsheet first but that would take forever so what I did was base the order off the OVERALL RATING in the spreadsheet. So the higher rated QB would go into QB1, next rated QB2....and so on. One issue I found was when 2 players overall rating is the same, based on how the editor sorts it before it's imported, you could get either player as QB1. Example is Tua Tagovailoa and Teddy Bridgewater are both rated 75 so sometimes the editor makes Bridgewater QB1 which isn't correct. Easy fix is to fix it after the import then SAVE it or just edit it within the spreadsheet, just change Tua overall rating to 76 and you're done.

Please contact me with any bugs or anything else you would like to see in the Editor. Adding the Importing from Excel should speed up the process even more, hope this helps anyone out there who loves the older Madden games as much as I do.
