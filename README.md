# The MiSTer Database For Game Manuals (POC) 

This is a POC database for the MiSTer project that downloads .txt game FAQs to the relevant folder within "/media/fat/docs".  These can be loaded from within the core's OSD by selecting the "Help" option.

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/faqs]
db_url = https://raw.githubusercontent.com/ajgowans/faqs.json.zip
```

NOTE: THIS IS A PROOF OF CONCEPT AND THE DATABASE SIZE IS LARGE

 ## Currently Included Cores With FAQs

- 32x
- CD-i
- Jaguar
- Jaguar CD
- SNES
- WonderSwan
