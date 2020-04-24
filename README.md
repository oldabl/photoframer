This little project can frame your photos into mockup rooms with frames.
You can use any mockup you want, portrait, square or landscape, and frame any photo you want to the right frames.
The program will frame all landscape photos into landscape frame mockups, portraits into portrait frame mockups and square into square frame mockups.
It's all automatic if it's set right (easy).

1. Get the mockup frame information
Take a mockup file with a frame in it. You need to know where the actual photo frame is in the mockup file.
To do so, use the program kshhhtest.py.
It runs as such in a terminal:
  python kshhhtest.py path/to/mockup framewidth frameheight framestartx framestarty

Where you started the command, check the file "isItFramedOk.jpg".
If the photo fits perfectly into the mockup frame, then rename your mockup file with the suggestion in the terminal.
If not perfect, reiterate with different parameters.

2. Frame all your photos
Now that you have your mockups renamed okay, put all your mockups in the same directory.
Put all your photos you want to frame in another directory.
In a terminal, run:
  python kshhhactivate.py path/to