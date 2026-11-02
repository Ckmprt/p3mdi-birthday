# P3MD Birthday Video

A browser tool that makes a 12-second 1080×1920 birthday video for P3MD members.

- Four styles: Sinema, Arcade, Poster, Tenun
- Removes the photo background in the browser (U2-Net human segmentation, TensorFlow.js); nothing is uploaded anywhere
- Lines up an existing cutout PNG with its photo automatically
- Editable name, date, wish, footer and logo; saves MP4 (or WebM) in Chrome or Edge

Static site: `index.html` plus the model weights in `seg/`. No build step.

Deploy on Vercel: Add New → Project → import this repository → Framework preset "Other", leave build and output settings empty → Deploy.
