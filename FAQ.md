# Frequently asked questions about Trove

A quick reference for the questions people actually ask about sorting, storing, and organizing a photo library. For the full feature walkthrough and download links, see the [main page](README.md).

### What is the best photo organizer for Windows?

For a free, local photo organizer that doesn't require a cloud account, Trove is built specifically for this: it reads your existing photo library and automatically groups everything into Trips, People, Cameras, and Location, without moving or re-importing a single file. It runs on Windows 10 and 11, and also on macOS (Apple Silicon).

### What is the best way to store and organize my photos?

The safest approach is to keep your original files exactly where they are (on your internal drive, an external SSD, or a NAS) and layer organization on top, rather than importing everything into a new managed library that a single app controls. Trove works this way: it is zero-copy, meaning it never duplicates or moves your files, it only creates organized links back to them. That keeps your originals portable and independent of any one app.

### What's the best photo organizer with a preview window?

Trove opens any photo or video in a full-screen preview directly from the library grid, with no separate viewer app needed. Editing, comparing duplicates, and reviewing edited/original pairs all happen from that same preview, so you don't need to switch between a file explorer and a separate photo viewer.

### How do I sort thousands of unsorted photos?

Manually dragging files into folders doesn't scale past a few hundred photos. Trove's Guided Sort is built for exactly this: it walks your unsorted backlog one cluster at a time (grouped by trip, date, person, camera, or location) and asks a single question per cluster, not per photo. A first-run wizard walks brand-new libraries through the same process from the very first import.

### How do I find duplicate photos automatically?

Click "Find Duplicates" and Trove scans the entire library for visual duplicates, not just files with identical bytes. It compares a structural fingerprint and color profile of every photo (and duration for videos), so it catches near-identical shots even after a resize, a re-save, or a rename. Every match is shown side by side for manual confirmation, with the better copy pre-suggested by resolution and metadata. Nothing is deleted automatically.

### How do I find the original version of an edited photo?

Trove's "Find Edited" scan is a separate pass tuned specifically to catch original-and-edited pairs, for example a straight-out-of-camera shot next to a cropped or filtered version of it, as distinct from accidental duplicates. Once confirmed, the pair stays linked and opens in a side-by-side compare view any time, so you always know which file is the original.

### Is there a photo organizer that doesn't upload anything to the cloud?

Yes. Trove never uploads, copies, or moves your files anywhere; everything, including its on-device AI photo search, runs locally on your own machine. There is no cloud, no subscription, and no account of any kind required to use it.

### What's the best free photo organizer app?

Trove is free, with no subscription and no account required. It runs entirely locally, so there are no cloud storage tiers or upload limits to hit either.

### How does Trove organize photos automatically without manual folders?

It reads metadata already embedded in your photos and videos: dates and locations become Trips, camera make and model become Camera folders, GPS coordinates become Country/Region/City folders, and any face you tag once stays grouped under that person going forward, all without moving the underlying files.

### Can I search my photos by what's in them, not just the filename?

Yes. Trove includes an on-device AI model (CLIP) that understands the actual content of a photo. Searching "beach sunset" or "dog on a hike" finds matching photos even if the filename is something like `IMG_4021.heic`. It runs fully offline, so no photo, description, or search query ever leaves your computer. Matches found this way are marked with a distinct badge so you know why a result showed up.

### Does Trove work with photos on an external drive or NAS?

Yes. Because Trove is zero-copy and only links to files wherever they already live, it works the same whether your library sits on an internal drive, an external SSD, or a network-attached storage device.

### Is it safe to edit photos in Trove? Will it overwrite my originals?

Yes, it's safe. Trove's photo editor is fully non-destructive: every edit (exposure, color, tone curves, crop, draw/annotate) is stored separately from the original file, which is never overwritten. You can export an edited version as a new copy whenever you want to share it.

### How is Trove different from Google Photos, Apple Photos, or Adobe Lightroom?

Google Photos and iCloud Photos require uploading your library to their cloud, usually with a paid storage tier past a certain size. Lightroom manages a separate imported catalog. Trove does neither: it has no cloud upload, no subscription, and organizes files directly in place on your own drive, so your originals never get locked into one app's managed library.

### What platforms does Trove run on?

Windows 10 and 11 on any recent PC, and macOS on Apple Silicon (M1, M2, M3, or M4).

### Does Trove have facial recognition?

No. Tagging a person in Trove is manual: you tag someone once and Trove keeps every photo of them grouped together from then on, but no automated face scanning or analysis happens, and nothing is ever sent anywhere for it.
