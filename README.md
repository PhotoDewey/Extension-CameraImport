# Camera Import — PhotoDewey Extension

Import photos from USB-attached cameras, SD card readers, and other removable
storage directly into your PhotoDewey library. Photos are moved or copied into
your library's import folder — no more manual file shuffling.

---

## Features

- Auto-detects connected USB drives and SD cards at dialog open
- Move (default) or copy files — your choice
- Optional date-organised subfolders (year / month / day)
- Optional album creation for the imported batch
- Duplicate detection — the same photo is never imported twice
- Full EXIF/IPTC/XMP metadata preserved
- Thumbnails generated immediately so browsing is fast

---

## Supported File Formats

| Format | Extensions |
|--------|-----------|
| JPEG | `.jpg`, `.jpeg` |
| RAW — Nikon | `.nef` |
| RAW — Canon | `.cr2`, `.cr3` |
| RAW — Sony | `.arw` |
| RAW — Olympus | `.orf` |
| RAW — Panasonic | `.rw2` |
| RAW — Digital Negative | `.dng` |
| RAW — Fujifilm | `.raf` |
| RAW — Pentax | `.pef` |
| RAW — Samsung | `.srw` |
| TIFF | `.tif`, `.tiff` |
| PNG | `.png` |
| WebP | `.webp` |

---

## Importing Photos

1. Open the **Import** menu and choose **From Camera / USB Device…**
2. Select your device from the drop-down, or click **Browse…** to pick any folder.
   Click **↺** to refresh the device list if you just connected a device.
3. Choose **Move files** (recommended — removes photos from the device after import)
   or **Copy files** (keeps originals on the device).
4. Optionally check **Organize into date folders** to sort photos into year/month/day
   subfolders inside your import folder.
5. Optionally check **Create album** and enter a name to group the imported photos.
6. The file count and total size are shown as a preview.
7. Click **Import**. A progress bar tracks the operation file by file.
8. When finished, a summary shows how many photos were imported, duplicates skipped,
   and any errors. Errors are written to the PhotoDewey log file.

---

## Duplicate Detection

Before importing each file, PhotoDewey checks whether an identical image already
exists in the library (by pixel content, then by filename and size as a fallback).
Duplicates are skipped and counted in the summary — they are never imported twice.

---

## Plugin Version

1.0
