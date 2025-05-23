# We lost the flag

Sorry everyone, we unfortunately lost the flag for this challenge.

**SHA256:** `d1058ed414e6e45f4d2c7cc41baf73b3778a80be18cdf2d6470348c72ab01dfd`

## Solution

Players are given a corrupted file, `lost.png`, however, upon inspecting the magic bytes/header of the file with something like `xxd lost.png | head -n 1` you will see that the magic bytes are not for a PNG, but rather a JPEG. 

To add some flare to this, the magic bytes are swapped further. You must correct the magic bytes to be the same as a JPEG file header.

> `FF D8 FF E0 00 10 4A 46 49 46 00 01`

Finally, you must change the file extension to `.jpg` to reveal the flag in the image.

## Flag

> `CIT{us1ng_m4g1c_1t_s33m5}`