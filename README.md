# NOTE ABOUT THIS FORK.

This is just a personal fork of mine that changes the default time delay from 6 to 200.

In my experience, mainly with Linear 10bit, you need a much larger delay for the bruteforce attack to work. For me it starts working around ~200, but 255 is best.  Around 150 that occasionally works, but not reliably.  But the default of 6 never works for me.

Adjust the time delay by *holding* the up button on the attack screen. A tap saves, but holding it up brings you to the view where you can adjust the time delay.

Ideally you should compile this yourself, but if you trust my binary, you can download it from this repo or the release page.

### To install this fork
- Download `subghz_bruteforcer_slow.fap` from releases of repo.
- Mount your SD card, or plug in your flipper and use qFlipper to access the filesystem
- Copy `subghz_bruteforcer_slow.fap` to `apps/Sub-GHz/`.
- Now on your Flipper you can go to Apps->Sub-GHz and open the new Sub-GHz Bruteforcer.

NOTE: In the app listing both this version and any prior versions will appear with the same name.  Once opened, this version will show the version number with '-SLOW' at the end.


# SubGHz Bruteforcer Plugin for Flipper Zero

SubGhz Bruteforcer from [Unleashed Firmware](https://github.com/DarkFlippers/unleashed-firmware)

### Disclaimer

This software is for experimental purposes only and is not meant for any illegal activity/purposes.
We do not condone illegal activity and strongly encourage keeping transmissions to legal/valid uses allowed by law. 

### Supported Protocols:

#### CAME

- CAME 12bit 303MHz
- CAME 12bit 307MHz
- CAME 12bit 315MHz
- CAME 12bit 433MHz
- CAME 12bit 868MHz

#### NICE

- NICE 12bit 433MHz
- NICE 12bit 868MHz

#### Ansonic

- Ansonic 12bit 433.075MHz
- Ansonic 12bit 433.920MHz
- Ansonic 12bit 434.075MHz

#### Holtek

- Holtek HT12X 12bit FM 433.920MHz (TE: 204us)
- Holtek HT12X 12bit AM 433.920MHz (TE: 433us)
- Holtek HT12X 12bit AM 315MHz (TE: 433us)
- Holtek HT12X 12bit AM 868MHz (TE: 433us)
- Holtek HT12X 12bit AM 915MHz (TE: 433us)
#### Chamberlain

- Chamberlain 9bit 300MHz
- Chamberlain 9bit 315MHz
- Chamberlain 9bit 390MHz
- Chamberlain 9bit 433MHz
- Chamberlain 8bit 300MHz
- Chamberlain 8bit 315MHz
- Chamberlain 8bit 390MHz
- Chamberlain 7bit 300MHz
- Chamberlain 7bit 315MHz
- Chamberlain 7bit 390MHz

#### Linear

- Linear 10bit 300MHz
- Linear 10bit 310MHz
- Linear Delta 3 8bit 310MHz

#### UNILARM

- UNILARM 25bit 330MHz (TE: 209us) (only dip switch combinations, not full 25bit bruteforce)
- UNILARM 25bit 433MHz (TE: 209us) (only dip switch combinations, not full 25bit bruteforce)

#### SMC5326

- SMC5326 25bit 330MHz (TE: 320us) (only dip switch combinations, not full 25bit bruteforce)
- SMC5326 25bit 433MHz (TE: 320us) (only dip switch combinations, not full 25bit bruteforce)

#### PT2260

- PT2260 24bit 315MHz (TE: 286us) (only for 8 dip switch remote, not full 24bit bruteforce)
- PT2260 24bit 330MHz (TE: 286us) (only for 8 dip switch remote, not full 24bit bruteforce)
- PT2260 24bit 390MHz (TE: 286us) (only for 8 dip switch remote, not full 24bit bruteforce)
- PT2260 24bit 433MHz (TE: 286us) (only for 8 dip switch remote, not full 24bit bruteforce)

#### Additional

- BF Existing dump works for most other static protocols supported by Flipper Zero
