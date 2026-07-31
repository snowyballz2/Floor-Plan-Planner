# Window photos

Full-size window photos are **not** synced (only a small thumbnail is). To see
them full-size on your Mac, keep the actual image files in a folder and point the
app at it. Filenames are what match a photo to its file — every photo shows its
filename, and the app keeps names unique.

## Getting the files

- **Uploaded photos** already have their filename — copy those same files into the
  folder (AirDrop, iCloud Drive, cable…).
- **Photos taken in the app**, or anything only on another device: open the photo
  in the app, tap **⤓ Save file** (downloads with the correct name), then move it
  into the folder.

## Viewing them full-size

**Live site in Safari (or any browser):** open a window's **Photos** section, click
**Load photos folder**, and pick the folder holding the files. The images load
locally for that session — nothing is uploaded (Safari's "upload" warning is just
its standard wording for folder access; the app only reads the files). You re-pick
the folder each time you reopen the app.

**Chrome / Edge, or the app installed to the dock (PWA):** same **Load photos
folder** button, but the choice is remembered and re-used on later visits.

**Running the local dev server** (`floorplan` preview): drop the files into *this*
`photos/` folder next to `index.html` and they're picked up automatically — no
button needed.

---

Files in this folder (other than this README) are git-ignored, so any images you
drop here stay on your machine and are never pushed to the public site.
