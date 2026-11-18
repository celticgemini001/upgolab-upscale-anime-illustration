# Upscaling Line Art Without Destroying the Lines

Measured: at 4x, interpolated upscaling loses 12% of the ink pixels in line art. Sharpening adds 20% back — and that excess is what turns a drawn line into a glowing smear.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-upscale-anime-illustration/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
