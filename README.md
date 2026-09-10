# Trove

Your photos and videos, finally organized. Not a single one of them ever leaves your computer.

Trove is a free, local-first photo organizer for Windows and macOS. It never uploads, copies, or moves your files: it just organizes links back to them, exactly where they already live on your drive. No cloud, no subscription, no account required. If you've been searching for how to sort a huge, messy photo library, how to find duplicate photos, or how to find your old edited shots again, this page covers exactly what Trove does and how it works.

<p align="center">
  <a href="https://github.com/Gilouloum/Trove-releases/releases/download/latest-build/Trove-Setup.exe">
    <img src="https://img.shields.io/badge/Download-Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white" alt="Download for Windows">
  </a>
  &nbsp;
  <a href="https://github.com/Gilouloum/Trove-releases/releases/download/latest-build/Trove-arm64.dmg">
    <img src="https://img.shields.io/badge/Download-macOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Download for macOS">
  </a>
</p>

<p align="center"><sub>Windows (any recent PC) · macOS (Apple Silicon, M1/M2/M3/M4)</sub></p>

---

![Trove's library grid view, sorted by trip](screenshots/library-grid.png)

---

## Why a local, zero-copy photo organizer

Every other photo app wants to upload your library somewhere: a cloud, a subscription, someone else's servers. Trove doesn't. It's zero-copy, meaning it never duplicates or moves a single file. Every photo card you see in Trove is just a pointer back to the real file, sitting exactly where it already was, on any drive: internal, external SSD, or NAS. Nothing is sent anywhere, nothing changes unless you change it. You stay the only owner of your own memories.

## Organize your photo library automatically: trips, people, cameras, and location

Stop manually dragging thousands of files into folders. Trove reads what's already in your photos and organizes them for you:

- **Trips.** Photos and videos are grouped into trips automatically as you import them, ready to browse or relive on the 3D Globe.
- **People.** Tag someone once and Trove keeps every photo of them together in one folder. Tagging is manual: Trove has no facial recognition, so who's in your photos is never analyzed or sent anywhere.
- **Cameras.** Each photo's camera make and model is read from its metadata and sorted into its own folder automatically. Shooting with two of the exact same camera model? Camera Profiles teach Trove to tell them apart by filename pattern instead.
- **Location.** Country, region, and city are looked up from each photo's GPS data, so your library can be browsed by where you actually were.
- **Categories and custom sections.** Build your own sidebar sections, with your own name, icon, and color, for anything that doesn't fit trips or people.

<!-- SCREENSHOT: sidebar expanded, showing Trips/People/Categories/Cameras/Location -->

## Never sort a photo library by hand again: Guided Sort

Wondering how to sort thousands of unsorted photos without losing a weekend to it? That's exactly what Guided Sort is for. It walks your "To Sort" backlog one cluster at a time (grouped by trip, date, person, camera, or location) and asks a single question per cluster instead of per photo. A first-run wizard walks brand-new libraries through the same idea from your very first import.

<!-- SCREENSHOT: Guided Sort or Getting Started wizard screen -->

## Find duplicate photos automatically

Click "Find Duplicates" and Trove scans your entire library for visual duplicates, not just identical files. It compares a structural fingerprint and color profile of every photo (and, for videos, duration) to catch near-identical shots even after a resize, a re-save, or a rename. Nothing is ever deleted automatically: every group is shown side by side for you to confirm, with the better copy pre-suggested by resolution and metadata.

<!-- SCREENSHOT: Find Duplicates side-by-side review screen -->

## Find and compare edited photos

"Find Edited" is a separate scan, tuned to catch original-and-edited pairs (a straight-out-of-camera shot next to your filtered or cropped version of it) rather than accidental copies. Confirmed pairs link together and open in a side-by-side compare view any time, so you can always find your way back to the original.

<!-- SCREENSHOT: edited-photo compare view -->

## Search your photos by what's actually in them, with on-device AI

Type what you remember, not what the file is named. Search "beach sunset" or "dog on a hike" and Trove finds it even if the filename is `IMG_4021.heic`, using an on-device AI model (CLIP) that understands what's actually in a photo, not just its metadata. It runs entirely on your computer: no photo, description, or query is ever sent anywhere. Results found by content instead of filename or tags carry a 🧠 badge, so you always know why a match showed up.

<!-- SCREENSHOT: search results showing the AI-match badge -->

## Edit photos without leaving your library

Right-click any photo for a full, non-destructive editor: exposure, contrast, highlights, shadows, whites, and blacks under Light; RGB tone curves under Tone; saturation, vibrance, temperature, and 8-band HSL color adjustments under Color; rotate and straighten; and a freehand draw/annotate layer. Every edit is stored separately from your original file, which is never overwritten, and can be exported as a new copy whenever you want to share it.

<!-- SCREENSHOT: Photo Editor open on a photo -->

## Relive your trips on a 3D globe

Every geotagged photo and video is plotted on a real-terrain 3D globe, zoomable all the way down to street level. "Relive Trip" opens on an overview of the entire trip first, then lets you step through it day by day.

<p align="center">
  <img src="screenshots/globe-overview.png" width="49%" alt="Globe view showing trips across the world with trip cards">
  <img src="screenshots/globe-zoom.png" width="49%" alt="Globe view zoomed into a single trip">
</p>

## More, worth knowing about

- **Best Of.** A library-wide highlight reel, separate from per-folder pinning: star anything, anywhere, and it shows up in one place.
- **Live Photos & Burst review.** Live Photos play their motion clip in one click. Rapid-fire bursts collapse into a single card, so you pick a favorite instead of scrolling past ten near-identical shots.
- **Drag & drop.** Drop a folder in and Trove imports it as a new trip. Drop loose files in and they're added straight to your library.
- **Automatic backups.** Your library's organization (folders, tags, edits) is backed up automatically as you work, with automatic recovery if anything ever gets corrupted. Your original photo and video files are a separate matter: since Trove never copies or moves them in the first place, back those up the normal way, same as you would without Trove.

---

## Installing

**Windows:** run the downloaded `.exe`. Windows will show a blue "Windows protected your PC" screen. That's just because the installer isn't signed with a paid certificate yet, not a sign of a problem. Click **More info → Run anyway**, then follow the installer.

**macOS:** open the downloaded `.dmg` and drag Trove into Applications. On first launch, macOS will say it "cannot be opened because Apple cannot check it for malicious software." Right-click (or Control-click) the app → **Open** → confirm. You only need to do this once.

Trove checks for updates automatically after that. No need to come back here for future versions.

---

<sub>This repo only ever contains the built app. Trove's source code is closed. If you're looking for the app itself, the buttons above are all you need.</sub>
