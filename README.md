# Nightcore.sh
A Bash script that allows you to easily create "Nightcore" versions of songs.

## Features
- Creates visual effects (a gliding background and audio visualizer) using only FFMPEG
- Designed to work with lossless files, by using lossless formats in all internal processing steps. 
- Preserves audio quality whenever possible by avoiding resampling, using lossless formats internally, and using the high quality SoX resampler whenever resampling is absoutely required.
- Offers lossless and various different lossy outputs (these can be enabled by uncommenting the bottom lines of the script).
- Offers video output at resolutions as high as 4K 60fps

## Dependencies
- GNU Coreutils or [untested] Busybox (for running the script)
- Bash (for running the script)
- FFMPEG (for encoding the video)
- SoX (for encoding the audio)
- Waifu2xcpp (for better image upscaling)

## Usage
Once dependencies are installed, download the script to your computer. Then, open the script, and adjust the built-in options as you see fit (there are options both at the beginning and the end of the script).

Once the script is configured, name your input files `input.flac` and `input.png`, and then run the script like so:
`bash nightcore.sh [speed multiplier]`. Don't include the brackets. If the `input.png` file is missing, an audio-only output file will be created.

Useful speed multipliers range from 1.1 to 1.3, different songs will likely need to be set to different speeds.

When running the script, please make sure you have at least 2GB of space available in your /tmp directory, and 2.5GB of available system RAM.

## Demos
Want to see what this script is capable of? Some demo videos are posted below.

Zedd - I want you to know (1.2x speed): https://streamable.com/dr30j

OneRepublic - Counting Stars (1.2x speed): https://streamable.com/w39xa

TheFatRat - The Calling (1.2x speed): https://streamable.com/p5uwe
