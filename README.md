# nrubik
An N-Curses Based, Virtual Rubik's Cube

NRubik was made due to the severe lack of n-curses based virtual Rubik's cubes. This very possibly might be the first one. 

# What does it look like?

Something like this:

![Screenshot](/nrubik-screenshot.png?raw=true)

Here is it solved (Yes, it's possible):

![Screenshot](/nrubik-screenshot-solved.png?raw=true)

# How do I install it?

Simply download the single, small "nrubik" python script and run it with a curses supported python2 or python3 interpreter. (Yes, the script works with both python2 and python3 :)

If you want a list of commands (macOS, BSD or Linux only):

    git clone https://github.com/linuxcowboy/nrubik.git
    cd nrubik
    chmod +x nrubik
    # To install globally
    cp nrubik /usr/bin/
    # To install locally (this might not work depending on the machine)
    cp nrubik $HOME/bin/

# No. How do I _install_ it?

What, you mean with a package manager? See here later for updates.

# Why is orange magenta?

On 8 color terminals, there is no orange but there is magenta. If you're confused why it's labeled orange in the first place, on an ordinary Rubik's Cube that is where orange would be.

# How is it best played?

Use a new terminal window/profile with a big font size (e.g. Monospace 20).

Coordinates and buffer sizes are for a 80x24 screen.

