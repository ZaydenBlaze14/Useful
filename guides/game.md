# Misc Stuff for Games



### Game Launchers
 <pre>1. EA games bought on Steam do not actually disable the origin overlay even if you have disabled it in   the launcher. 
   
    -  This causes stutters and causes some keys to stop giving input in the game.
    -  If you have noticed your character stopping even when you have pressed the button, this might fix it.
    
    > Rename the "igo64.dll" to "igo64" on <b>C:\Program Files (x86)\Origin</b>
</pre>
<p>&nbsp;</p>

<pre>2. Epic Games Launcher still does not have the functionality to remember games on external hdds. Having to reverify them is a pain.

    - Go to <b>C:\ProgramData\Epic\EpicGamesLauncher\Data\Manifests</b>
  
    - Modify the <b>ManifestLocation, InstallLocation, and StagingLocation</b> values in the manifest to point to the new install directory using notepad.

    - Similarly for Unreal open <b>C:\ProgramData\Epic\UnrealEngineLauncher\LauncherInstalled.dat</b> and change <b>InstallLocation</b>
</pre>

