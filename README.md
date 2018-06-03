# Wine-fornite
A set of patches to make fortnite possibly work with Wine

Credits:
This is made by reddit.com/u/guy1524, I just made it into a github repository for a lutris build.

I have no idea if this works and/or if it can get you banned. Use with caution.

## The original post on reddit:

This is *not* guaranteed to work.  If you have any issues, send me them, and I'll change the guide.  This is tested on arch, so don't send me issues if you're not on it.  Also, wine-gecko is probably required.  By the way, if you a battleye user like me, you are shit out of luck in terms of battle royale.  );

1) Compile wine-staging-git on the AUR to grap dependencies, or get them another way, idk how

2) Clone this repo using `git clone https://github.com/OfficialBAMM/wine-fortnite.git` 

3) Compile it, you can find a guide for how to compile wine here

4) Install Epic Games Launcher.  Download the msi, run it through winefile (double click on it) or msiexec, and when it goes to white and red, close wine.

5) Add prefix/drive_c/Program Files (x86)/Epic Games/Launcher/Portal/Binaries/Win32/EpicGamesLauncher.exe as an application in winecfg, and disable shcore for it.

6) To launch the launcher, be sure to provide it with "-SkipBuildPatchPrereq -OpenGL" parameters

7) If fortnite doesn't open when you click on it, kill the fortnite process and try, try again.
