# Bits 'n Pieces

Somewhere in these digital fragments lies what you've been searching for your entire lifetime, or really just this weekend ;)

**SHA256:** `4b52731748484ecaa9ba3a5c8ec455675c78d0e3f8ac349a2a54e5e1f0cbb2a1`

## Solution

The challenge-related file is bitmap cache from a Remote Desktop session on Windows. Running a tool such as [BMC-tools](https://github.com/ANSSI-FR/bmc-tools) will output the `.bmp` files from the cache. 

From there, using a tool such as [RDPieces](https://github.com/brimorlabs/rdpieces) you can piece the images together like a puzzle and get the flag from the command prompt that was open in the system.

Alternatively, by just scrolling through all the `.bmp` files you can get an idea of what the text is displaying and piece the flag together by simply browsing the image previews in the output folder.

## Flag

> `CIT{c4ch3_m3_if_y0u_c4n}`