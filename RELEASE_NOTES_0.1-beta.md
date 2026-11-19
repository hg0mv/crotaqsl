# CROTA QSL 0.1-beta

First beta of CROTA QSL – QSL cards for **CROTA (Church Ruins On The Air)** activators.

Open your activation log (ADIF), choose the CROTA reference, and the photo of the church ruin becomes the background of your QSL card. Print full cards or labels as PDF, or save one eQSL picture per station.

## Highlights

- Reference list and photos downloaded from crota.hu, kept on your computer for offline use; a local `references.json` can be used too
- Reference picker with search (accents optional)
- QSOs logged at other references (`MY_SIG_INFO`) are hidden automatically
- CB and PMR446 QSOs show the channel (`CB 19`, `PMR 4`) instead of MHz
- Your call comes from the log (`STATION_CALLSIGN`), so ham and CB activations both get the right call
- Card designer: picture, box, text with placeholders, QSO table; move and resize with the mouse
- PDF cards (4 per A4 page), PDF labels (3 × 8), eQSL JPG pictures
- `qsl_sent_*.adi` after printing, to mark the QSOs as sent in your logbook
- With no log open, a sample card can be printed to try the design and the printer
- English and Hungarian interface

## Downloads

- `crotaqsl-0.1-beta-windows-x64.zip` – Windows 10/11: unzip and run `crotaqsl.exe` (no installation)
- `crotaqsl-0.1-beta-linux-x86_64.tar.gz` – Linux x86-64 (X11); needs `curl` for the download
- `crotaqsl-0.1-beta-src.tar.gz` – source code

Windows SmartScreen may warn on the first start because the program is not signed: click **More info → Run anyway**.

## Known limitations

- WebP photos are not supported (JPG and PNG are, including progressive JPEG).
- The PDF contains the cards as pictures.

This is a beta – please report problems on the Issues page.
