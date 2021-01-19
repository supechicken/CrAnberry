# CrAnberry
Rooting the ChromeOS Android Subsystem post v77

After update v77 of ChromeOS, android was updated to version 9 and nolirium's [aroc project](https://github.com/nolirium/aroc) no longer worked. This is a script heavily inspired by their initial work, but made much more simple, and with the restrictions of at least ARMv7 v84 in mind.

# Disclaimer: I am not responsible for any damage caused by this script.

To use it locally, save the CrAnberry.sh file to your Downloads folder, then copy it to your `/usr/local/bin` folder, and run `sudo /usr/local/bin/CrAnberry.sh`

To use it online, copy and paste the following in crosh: <insert later when I'm not tired>

Currently this script does not fully work. It can generate an Android image with `su` installed, but it does not grant root access from within the android container, even with SELinux set to Permissive. Still looking into this.
