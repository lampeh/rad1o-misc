# Wideband FM
Wideband FM examples for GNU Radio and HackRF / rad1o

## Crosby Stereo-FM transmitter and receiver
The Video2000 of FM stereophonic broadcasting.  
https://en.wikipedia.org/wiki/Crosby_system

Usage:  
	mpg123 -s -v http://stream-uk1.radioparadise.com/mp3-128 |sox -t raw -c 2 -b 16 -e signed -r 44100 - -t wav -c 2 - |./crosby_tx.py
