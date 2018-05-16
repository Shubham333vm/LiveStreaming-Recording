# LiveStreaming-Recording
LiveStreaming and Recording by using Grestreamer
-------Gstreamer-1.0v
-------OS-Ubantu-16.04.3

Objective- To make multiple files each of 10 minutes.

In this code i am trying to call two threads simltaneously and they will make two seperate files each of 10 minutes 
by help of sleep method and then they join main method and exit .So i get only two files.
And if i try to make a recursive call then they will override a new file on the same old file. So again i left with
two files.

So how to disconnect a thread from a particular file and make a new file recursively after 10 mintues?

It can be done by using multifilesink element in gstreamer but i m not able to make a use of it and that's why i m trying to 
do it with the help of threads only.
