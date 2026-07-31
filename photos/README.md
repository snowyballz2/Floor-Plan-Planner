# photos/

Drop window photo files here (any image format) to have them show full-size in
the Floor Planner app on this Mac.

## How it works

- Every photo you add in the app (camera or upload) gets a **filename**, shown in
  its tooltip and saved/synced with the plan (the file itself is **not** synced —
  only a small thumbnail is).
- When the app is opened from this folder's local server, it looks for a file of
  that exact name in `photos/`. If it's here, the real full-size image is shown
  in the grid and the viewer. If not, the synced thumbnail is used.

## Getting the files here

- **Uploaded photos** already have their original filename — copy those same
  files into this folder (AirDrop, iCloud Drive, cable, etc.).
- **Photos taken in the app** (or anything you only have on another device): open
  the photo in the app, tap **⤓ Save file**, and it downloads with the correct
  name — then move it into this folder.

Names must match exactly. The app avoids duplicate names automatically.

Files in this folder (other than this README) are git-ignored, so they stay on
your machine and are never pushed to the public site.
