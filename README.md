# Sandbox

## Overview
Public examples and ideas for future reference.

## Bash Scripts

[MakePlClips](https://github.com/hieberr/sandbox/blob/master/Bash/MakePlClips.sh) - I am creating a music game which uses many music files exported by Reaper. I export the files so that the parameters I need (NAME, bpm, key, tempo, loop points) are in the name of the audio file.  I needed a simple shell script which would extract these parameters and stick them into a text file while renaming the audio file to just be NAME.wav. Once I have the audio files and their matching text files, I can import all of them into Unity where my custom AudioPlayer can interpret the extra parameters in the text file.
