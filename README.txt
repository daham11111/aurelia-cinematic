AURELIA ESTATES — SCENE 01 SCROLL STARTER
===========================================

Source: Your uploaded 8-second 1280x720, 24fps MP4 cinematic building film.
Pack: 96 WebP still frames at 12fps, 1280x720, quality 75.
Goal: Smooth-enough starter preview with 96 scroll-precise frames; production can use higher frame-rate sequences.

TEST ON WINDOWS / CHROME (NO POWERSHELL)
1. Right-click the downloaded ZIP file > Extract All.
2. Inside the extracted folder, double-click index.html.
3. Scroll DOWN and UP with the mouse inside Chrome.
4. Building frames should move forward/backward and freeze at a stopped scroll position.

CONTENTS
- index.html: self-contained cinematic demo (only local frame images needed)
- frames/: frame_0000.webp through frame_0095.webp
- CLAUDE_PROMPT.txt: paste into your ongoing Claude conversation after hosting assets
- manifest.json: filenames and metadata

IMPORTANT: Claude's regular chat file uploader does not list MP4 or ZIP as supported media inputs.
Do not expect dropping this ZIP into Claude Chat to give its live Artifact automatic access to the frames.

TO HOST FRAMES WITHOUT TERMINAL
1. Open GitHub and create a new PUBLIC repository called 'aurelia-cinematic'.
2. Click Add file -> Upload files.
3. Drag the contents of THIS extracted folder (index.html, manifest.json, frames folder) to GitHub.
   GitHub web upload supports at most 100 files per operation. Here there are 96 frames and
   3 additional files, within that limit. (Other content may need a second upload.)
4. Commit changes.
5. In Settings -> Pages, enable GitHub Pages from main branch, root (/).
6. Your hosted demo will appear at https://YOUR-USERNAME.github.io/aurelia-cinematic/ after deployment.
7. In the same Claude conversation as the AURELIA website, paste the URL and CLAUDE_PROMPT.txt.
8. Claude should integrate the hosted frame sequence into the existing scene component,
   without touching the other eight scenes or branding.

BROWSER NOTE: Some browser security settings may block certain local file accesses.
If the offline demo doesn't display frames, publishing via GitHub Pages uses standard HTTPS and avoids that issue.

PERFORMANCE
- Images total approximately 4 MB, loaded progressively.
- Frame sequences provide consistent backward and forward scrubbing.
- No autoplay; scroll controls frame index.
- Mobile reduced-motion option included.

Asset usage: AI depiction / concept visualization, not a verified physical property.
