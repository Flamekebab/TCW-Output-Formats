# The C Word Podcast Output Formats

The name isn't catchy but the idea is a program with a simple GUI (PyQT5) that deals with the finished episodes of [The C Word Podcast](https://thecword.show).

Each time the edit is finished multiple versions of the show need to be created (various codecs, channel counts, and bitrates).
This program should run on most things and handles all that in one step. 

Fire it up, feed it an input file, tell it where the outputted files should end up, decide whether you want all the formats or just MP3, then wait.

Once it's done it'll tell you.

To package it up into an executable:

    pyinstaller gui.py --name TCW-Transcoder --onefile -w

...probably.