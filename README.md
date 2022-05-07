# eduroam-connection-suite

## Skripte za povezivanje na eduroam mrežu

Skripte namjenjene za olakšano povezivanje na eduroam mrežu.

### eduroam-cert-gen

Skripta namjenjena generiranju ```wpa_supplicant``` konfiguracije. Može se navesti putanja do certifikata, može se urediti varijabla ```putanja``` unutar skripte. Skripta se koristi samo prilikom inicijalnog postavljanja mreže.

Certifikat se može preuzeti na [ovoj poveznici](https://installer.eduroam.hr/other_user.php?lang=hr) pod "CA root certifikat", ali pošto ovdje prvi put postavljamo internetsku vezu ne možemo certifikat programski preuzeti preko interneta nego ga moramo drugačije spremiti na naše računalo ¯\\\_(ツ)\_\/¯

### eduroam

Skripta namjenjena povezivanju na eduroam mrežu. Preporučljivo je instalirati ```dmenu```, iako skripta radi i bez njega. Dependency za hotspot je ```create_ap```.
