# 211BSD
Dumping ground for stuff related to 2.11 BSD Unix for PDP-11, particularly as it relates to Oscar's PiDP-11 (https://obsolescence.wixsite.com/obsolescence/pidp-11).

(Disk images based on Chase Covello's patch level 482 image: https://github.com/chasecovello/211bsd-pidp11)

# Updates
- Patch level 490
- Created getpatch script (in /usr/local) that will download the specified patch number, save it in /usr/src/patch and carve out the actual patch diffs and save as /tmp/###.patch. This script is a simplification inspired by the 211BSDupdater by Antoni Villalonga.
