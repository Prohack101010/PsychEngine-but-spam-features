1.22.0;

Rendering Mode was reworked (Windows only) - The MP4 is now automatically made for you, using FFmpeg! (You must put the FFmpeg .exe in the same folder as the JSEngine.exe for it to work, adding it to the Environment variables does NOT work!)
As well, you can customize the bitrate of your video! (also windows only)
Added some more spamcharting tools! you're welcome
Added "addWiggleEffect" as a lua callback
Added a state for when Rendering Mode finishes rendering a song
The options menus now have search bars to help you find that one option you need!
You can now add difficulty-specific songs by appending "-(difficulty name)" to the end of them
You can now change the chosen difficulty in the Chart Editor
Added an option to disable the icon bop limiter which looks HILARIOUS when there's spam with it turned on
Added an option to disable the icon bop if.. you just don't want the icons bopping
You can now make certain characters shake the screen, and the Health Drain steppers in the Character Editor now change in lower increments
Switched to note recycling instead of creating a new note every time
The engine no longer looks for "song-normal" if you put the difficulty as Normal in all lowercase/uppercase
Fixed the Guns Ascend thing crashing the engine if you played using a HUD type that didn't have an engineWatermark
Fixed Icon Bop Type defaulting to "Psych" which isn't an actual option
Fixed a bug where if the icons' positions were changed before the health bar tween was finished then they would stay stuck at whatever position they were in
Fixed a bug where disabling the Smooth Health Bar would result in icons being stuck on the left side of the screen
Fixed Rendering Mode not ending if you disabled the time bar
Finally fixed big icons being pushed down (however it did break the Strident Crisis icon bounce.. oops. I'll see if I can fix it in 1.23.0 or if I need to completely remove it)