# ConvAudio
Audio converter Script using ffmpeg

## Dependencies
- ffmpeg

## Conversions
-wav|flac|wv|m4a|aif|aiff|mp3|ape|alac

## Execution
- convaudio -d /myaudiofiles -i m4a -o flac 
(Will not remove original file after conversion)
- convaudio -d /myaudiofiles -i m4a -o flac -r
(Will remove original file after suceffull conversion)

![screenshot](https://i.postimg.cc/d0YjdRRG/shutter.png)

## Notes
- This tool works recursively , this means it will search inside input folder all files with selected extension to convert and sub folders
- It is advised to use ffmpeg using apt instalation to avoid missing codecs on manual compilation
- This tool does not write idtag on converted files , this means that on converted file the name,song and all other metadata will be empty . 
- Output converted files will be placed on same original file location
