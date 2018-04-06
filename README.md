minecrafty
==========

This is the one-stop script for starting Minecraft. This isn't a replacement for current
launchers, it's more a tool to help out with starting them up.

Features:
* Download commonly available launchers:
  * Default launcher (minecraft.net)
  * SKMCLauncher (sk89q.com, obsolete)
  * Digiex (obsolete and not kept up to date)
  * MagicLauncher
  * MultiMC (disabled for the moment until I find another download)
  * FeedTheBeast
  * Craftland
  * Technic
  * Minecraft Version Changer (TunkDesign) (probably obsolete)
  * Aether Launcher
* Download available release and snapshot versions of the minecraft client and server
* Execute any installed minecraft launcher, even the default one
  * Allocate memory for the launcher
  * Change screen brightness/gamma/resolution
  * Send output to a logfile
* Reset refresh rate on monitors after minecraft finishes
* Downloads the latest bukkit Recommended Build
* Starts a selected installed server

Requirements:
* A paid account for minecraft. Unpaid won't work, or at best you will have demo.
* Linux running in graphical (Xorg) mode. Minecraft won't work otherwise.
* Any version of Linux with bash 4 (FreeBSD may work, but only if you have bash 4 installed.)
  * This has NOT been tested with cygwin, as Windows has its own launcher.
* xrandr (available in most Linuxes.)
* awk (should be available in Linux by default.)
* wget (to fetch files.)
* Java (either OpenJDK, Oracle JDK or equivalents.)
* Other minecraft requirements (decent video card, recent machine, enough memory.)
* Some terminal, to run this script and see its output. Not absolutely mandatory, but you'll
  thank me if something goes wrong and you can see it.

Who this is for:
* People who use modified jars.
* People who use non-standard launchers.
* People who wish to tweak how minecraft starts up.
* Dual/multi-monitor setups where the second screen gets its refresh rate reset every time
  minecraft quits.
* People who want a single file to start whatever variant of minecraft they have,
  whether client or server.
* People who are reasonably comfortable with using a commandline. This program
  works well enough from .desktop files, but then you don't see any text information.

Who this is NOT for:
* People with no computer experience, who just want to run minecraft without
  any changes, additions or hassles. If the base launcher does what you want, then
  this script is not for you.
* People trying to run minecraft without having paid for it. This script
  will not help you. Minecraft is not overly expensive in comparison to some
  other games, and is most definitely worth it.


