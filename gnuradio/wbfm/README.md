# Wideband FM
	mpg123 -s -v http://stream-uk1.radioparadise.com/mp3-128 |sox -t raw -c 2 -b 16 -e signed -r 44100 - -t wav -c 2 - |./crosby_tx.py
