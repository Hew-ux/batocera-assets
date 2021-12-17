Batocera's official loading splash images and videos. Also included here are the website banners and logos based off of them. Source files are SVGs. You will need the Urba font installed to view the SVG files properly.

Customise your splash screen: https://wiki.batocera.org/splash_boot

# Regular splash screens

`logo.png` - The official splash image used by Batocera for its boot sequence, game loading, and other miscellaneous purposes.

`logo-4k.png` - A 4K version of the official splash image. This isn't actually used (yet).

`logo480p.png` - The official splash image used by Batocera for its boot sequence when the video mode is set to 480p (either by the device's defaults or manual user intervention). It is cropped to a 4:3 aspect ratio to match those devices better.

`logo-16-9-480.png` - For the OGSuper and devices with similar screens. This is rotated 270 degrees in some cases.

`logo-3-2-480.png` - For the original Odroid Go Advance. This is rotated 270 degrees in some cases.

`logo-240.png` - For the GPI Case.

`logo-3-2-1080.png` - Generic 3:2 version.

splash-video-3-Lichshield.mp4 - The current video splash image used in compatible platforms, created by Lichshield. A 4K version of this can be found at This file can be found at https://drive.google.com/file/d/1iVsw197aeJd0m6szmv3VW5M8FcCj3rav/view?usp=sharing

# Alternative designs are available in the alternatives folder.

`splash-image-<other-thing>.png` - Alterations of the main splash image, free to use for the promotion of Batocera.

`banner-simple.png` - For use with small banners that require clarity over presentation. This has a lot of the post-effects removed to appear more legibly at smaller rendering resolutions.

`banner-icon.png` - For use as Batocera's avatar/display picture/user profile picture. This has a lot of the post-effects removed to appear more legibly at smaller rendering resolutions.

`circle-avatar.png` - For sites that A. use circular avatar "holes" and B. don't feature a zoom and crop tool when uploading, ahem _reddit_.

# Seasonal alterations are available in the seasonal folder.

    # Happy New Year!
    [ $(date +%m/%d) -eq 1/1 ] && SEASON=newyear
    # Valentine's day
    [ $(date +%m/%d) -eq 2/14 ] && SEASON=valentine
    # Pi Day
    [ $(date +%m/%d) -eq 3/14 ] && SEASON=pi
    # Saint Patrick's day
    [ $(date +%m/%d) -eq 3/17 ] && SEASON=stpatrick
    # April Fools!
    [ $(date +%m/%d) -eq 4/1 ] && SEASON=aprilfool
    # Aurora Borealis
    [ $(date +%m) -eq 6 && $(date +%d) -gt 6 -lt 18 ] && SEASON=steamedclams
    # Batocera's anniversary.
    [ $(date +%m/%d) -eq 6/21 ] && SEASON=anniversary
    # Independence day
    [ $(date +%m/%d) -eq 7/4 ] && SEASON=independence
    # Aurora Australis
    [ $(date +%m) -eq 9 && $(date +%d) -gt 6 -lt 18 ] && SEASON=australis
    # International Talk Like a Pirate Day
    [ $(date +%m/%d) -eq 9/19 ] && SEASON=pirate
    # All Hallows' evening.
    [ $(date +%m/%d) -eq 10/31 ] && SEASON=halloween
    # Christmas time! Only true if month is December and date is less than 27.
    [ $(date +%m) -eq 12 && $(date +%d) -lt 27 ] && SEASON=xmas
    # Monkey day https://en.wikipedia.org/wiki/Monkey_Day
    [ $(date +%m/%d) -eq 12/14 ] && SEASON=monkey
    # Winter solstice
    [ $(date +%m/%d) -eq 12/21 || $(date +%m/%d) -eq 12/22 ] && SEASON=solstice
