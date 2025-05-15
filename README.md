# android-deGaFAM-shizuku
Android debloath és deGoogle kábellel valamint kábel nélkül Linux alatt

tl;dr

Android debloath és deGoogle kábellel valamint kábel nélkül Linux alatt:

I. Universal Android Debloater - régi
- gitlab.com/W1nst0n/universal-android-debloater

II. Universal Android Debloater GUI - új
- github.com/0x192/universal-android-debloater

III. Shizuku App és Canta modulja
- shizuku.rikka.app/download [moe.shizuku.privileged.api]
- f-droid.org/hu/packages/org.samo_lego.canta

IV. Systemless DeGoogler
- kistesó, bash customize.sh

kell
- motiváció, idetaláltál - ez pipa
- némi gyakorlat, 10 elrontott telefonból 8 megjavitott, felújitott
- sudo apt-get install adb fastboot heimdall-flash android-sdk-platform-tools
- build number . . . . developer options
- kábel és USB debugging vagy Wireless debugging, ez utóbbi elérése Android verzió függő
- droid-ify, repótelepités felmerülhet

nem kell
- root, amúgy is kimenőben a divatból, a tűzfal megfelelő védelmet nyújthat az adatszivárgás ellen, a netbank meg..
- com.google.android.gm, com.google.android.gms, com.android.vending..

I. Van kábel, működik az adatkapcsolat

- Az „Universal Android Debloater” korábbi, bash script futtatását lehetővé tévő verziója szerintem nagyobb mozgásteret biztosit, mint az új GUI-el fejlesztett változat.

- a telefon bekapcsolt és képernyőzár-ügyileg feloldott állapotban van
- terminál inditása az UAD mappájából
- bash debloat_script.sh
- nem köszi, 3, 3

..



III.  Nincs kábeles adatkapcsolat, csak töltődik jó esetben, így GPS-nek, ébresztőórának, bármi másnak még pont jó lesz

..
