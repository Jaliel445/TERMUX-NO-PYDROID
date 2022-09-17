# TERMUX-NO-PYDROID
Putting Jupyter Notebook On An Android Without Pydroid3
If you want Jupyter Notebook on your android, but found
out that pydroid3 isn't available, then this is your
lucky day.I have a way that it can be done, without pydroid3.

Just follow these instructions:

1: Go to Google Play and install Andronix, launch it.
2: In Andronix, go to the F-Droid download for Termux, install it.
(Termux in Google Play is depreciated and won't work)
When installed, go back to Andronix to choose your distro,
Debian works the best.
Follow the instuctions in Andronix.
When the distro is installed, type: python3 --version 
You should have version 3.8.8 installed automatically.
Next, upgrade pip with: python3 -m pip install --upgrade pip.
Now it's time to install Jupyter with: python3 -m pip install notebook
There will be some dependancies that will need installed, so
you will get an error. Install these dependancies with pip install or pkg install.
Next, reinstall Jupyter the same way.When finished and no errors come up, type: jupyter notebook
And there you have to copy a url to put in your address bar in your browser : http''''''
Make sure you do this from root.
To get to root, type ./start-debian.sh provided that you used that distro.
