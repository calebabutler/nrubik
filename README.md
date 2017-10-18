# nrubik
An N-Curses based, Virtual Rubik's Cube

NRubik was made due to the severe lack of n-curses based virtual Rubik's cubes. This very possibly might be the first one. 

# What does it look like?

Something like this:

![Screenshot](/nrubik-screenshot.png?raw=true)

Here is it solved (Yes, it's possible):

![Screenshot](/nrubik-screenshot-solved.png?raw=true)

# How do I install it?

Simply download the single, small "nrubik" python script and run it with a curses supported python2 or python3 interpreter. (Yes, the script works with both python2 and python3 :)

If you want a list of commands (macOS, BSD or Linux only):

    git clone https://github.com/cheertarts/nrubik.git
    cd nrubik
    chmod +x nrubik
    # To install globally
    cp nrubik /usr/bin/
    # To install locally (this might not work depending on the machine)
    cp nrubik $HOME/.local/bin/

# No. How do I _install_ it?

What, you mean with a package manager? See here later for updates.

# Why is orange magenta?

On 8 color terminals, there is no orange but there is magenta. If you're confused why it's labeled orange in the first place, on an ordinary Rubik's Cube that is where orange would be.

# There are so many features missing. Why?

I purposely left out some features so that any terminal geek can try out this virtual rubik's cube without having to learn how to rotate the cube or turn a side counter clockwise or do half turns. Don't get me wrong, this is a complete virtual Rubik's Cube, but avid Rubik's Cube solvers might be frustrated that this Rubik's Cube cannot be as easily turned and twisted. Another advantage of simplifying the interface, however, is that avid Rubik's Cube solvers now have a new challenge, and are forced to think of the Rubik's Cube in a different way.
