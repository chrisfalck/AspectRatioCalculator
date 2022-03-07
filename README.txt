I found myself wanting a program to automatically generate resolutions matching my monitor's native aspect ratio so I could use custom resolutions in NVIDIA control panel with minimal blur from scaling. I originally created a command line tool for this, but eventually decided it would be a fun exercise to create a very simple site to handle this, and maybe it will be useful for someone else out there too. 

I wrote and tested this on Firefox version 97.0.2, and I use some modern browser APIs, so your mileage may vary on different vendors and older builds.

Dark reader messes with the background so I have it disabled personally.

There are no external dependencies, just one index.html file which contains all of the JS and styles.

I threw this together in one day, so while I tried to find the obvious bugs, it's far from bullet proof, and you can crash your tab if you goof around with weird inputs.

I have an Azure storage account hosting this as a static website if you're just interested in using the tool. You can find that here: 
https://aspectratiocalculator.z13.web.core.windows.net/

Cheers!