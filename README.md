# Overview
Hey there, if you're reading this it means you're rad enough to take the time to help out with the Waking Titan riddle. Congrats. :)
Hopefully this Python notebook will give some people a few handy tools to play around with this hex data and figure out what to make of it.
I tried to expose a few options to play around with, but there's probably not enough here to do much alone. The goal is that:
1. People can quickly try ideas and plug them into other things
2. People without a coding background can play around with this data and see what they can find
Feel free to add on anything that seems helpful(or fix any issues you see, I'm pretty tired and this probably isn't exceptionally good code ;)  )

# What's included
- Easy access to the hex values
- Easy access to the blank field hex values(stolen with love from Sandsnake on the Waking Titan Phase 2 Discord channel)
- Encoding/decoding utils(as seen in the wheels from the email)
- Conversions to various periodic table values, as explained by r/TrialByDissonance in [this post](https://www.reddit.com/r/NoMansSkyTheGame/comments/6orsy9/waking_titan_megathread_phase_2_begins_edition/dkjzsoj/)

# Installation
If you have Python 3 and Jupyter and you know how to use them, you're all set. Start up a jupyter server and play around. Otherwise this is all you should need:
- Open up a command line
- Navigate to the directory where you downloaded these files(in particular, wt.ipynb)
  - In case you're new to this, on Linux/MacOS, you'll want to know the `ls` and `cd` commands, which stand for 'list' and 'change directory', respectively. On Windows use `dir` instead of `ls`
- Trust that I'm not tricking you into installing a virus(I'm not)
- Run the following commands:
  - pip install jupyter
  - jupyter notebook
- In your browser, open `localhost:8888`
  - Note that if this address isn't recognized, you'll have to debug this by looking at the output on your command line. Probably the most likely issue is the port number, which you can find by looking for an output akin to 'The Jupyter Notebook is running at: http://localhost:8888/'. The address listed there is the one that should work. Another common gotcha here is when the output on the command line says something like 'The Jupyter Notebook is running at: http://localhost:8888/?token=0123456789abcdef0123456789abcdef0123456789abcdef'; note the token here, and know that you'll need to include that token to authenticate to Jupyter that you are in fact the person running the notebook server.
  
# Contribution
Do that. If this is helping anyone out, please add anything that becomes relevant so that we can have more people with quick access to info about all this hex data.

# Misc Considerations
I work in a unix environment. I don't think there will be too much difference, but if you're new to Python(or Jupyter, in particular) you might run into issues installing Jupyter on Windows. I'm sorry, and I can try to help after I wake up tomorrow. :)
Also, ignore the .DS_Store file. MacOS puts it there automatically, and it's a hassle to get rid of so I just didn't deal with it. I promise it won't do anything to hurt your comp.

Also, there are some simple parameters in some of these cells, they're identified by variables in ALL_CAPS. These are the easiest way to play with different things to see what works, imo. Do what works for you though.
