Using the starter code file as a guide, I completed all of the functions required for the router.  The message 
recieved from a port is handled by handle_packet, where it is then sent out to the correct function to complete
the desired action based on the task listed in the packet.  Some of these functions delegate further to
complete some functionality required.

I tested my script by adding several "if DEBUG:" statements, so if I turned on debugging I could see a lot of 
useful information about what was actually happening.  This also allowed to me to easily turn off the DEBUG
functionality to read what the test script was telling me.


An issue that I had when working on this assignment is that when I was working with the starter code, I didn't 
really take the time to fully read through it to see everything that it did.  I kind of just saw that most of the 
functions were empty with #TODO, so I tried establishing a connection and reading messages.  After realizing that 
the starter code already did those things, however, the process was sped up a lot, and I was able to start working 
on actually processing the messages.

I also ran into a lot of time sink when I had simple syntax errors, as using vim on the ssh connection does not
do a great job indicating where exactly the syntax error is, compared to using an IDE.
