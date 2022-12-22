# ConvAudio 1.0
Audio converter Script using ffmpeg

## Dependencies
- ffmpeg

## Conversions
![screenshot](https://i.postimg.cc/3Nf6qX4W/conv.png)

## Execution
- convaudio -id /myaudiofiles -ic m4a -oc flac 
(Will not remove original file after conversion)
- convaudio -id /myaudiofiles -ic m4a -oc flac -r
(Will remove original file after suceffull conversion)
- convaudio -id /myaudiofiles -ic m4a -oc flac -od /converted_files 
(Will not remove original file after suceffull conversion and converted files will be placed on desired directory)

![screenshot](https://i.postimg.cc/d0YjdRRG/shutter.png)

## Switches
![screenshot](https://i.postimg.cc/wBVdVsVR/switches.png)

## Notes
- This tool works recursively , this means it will search inside input folder all files with selected extension to convert and sub folders
- It is advised to use ffmpeg using apt instalation to avoid missing codecs on manual compilation


