# ENCOUNTr_v1
A time and event tracker for tabletop RPGs
///// Welcome to /////////////////////////////////////////////////
//    ____  __  __  ____  ___   __  __  __  __  _______         //
//   / __/ /  \/ / / __/ /   / / / / / /  \/ / /__  __/  ____   //
//  / __/ / /\  / / /_  / / / / /_/ / / /\  /    / /    / __/   //
// /___/ /_/  \/ /___/ /___/ /_____/ /_/  \/    /_/    /_/      //
//                                                              //
///////////////////////////////////////////// V1.0 ///////////////

INSTRUCTIONS FOR SETUP:
------------------------------
SAVING YOUR GAME:
To ensure that your game is saved, type 'exit' to close the program. 
If you press 'X' to close the program while it's running you will 
lose your progress. You have been warned.

Your adventure information is saved whenever you close out. It will 
keep track of the day, what time it was when you stopped, and what the 
weather was like.  It will also save any events you added during the 
session.  
------------------------------
SETTING UP EVENTS:

Your adventure file is located in the 'saves' folder after it's 
created. You only need notepad to open it. This gives you a clear 
workspace to plan out world-changing events, holidays, deadlines 
and so on for a much more precise fantasy universe.

The ENCOUNTr program is set up to read your adventure documents
in a very specific way. They are set up as follows:

Line 1: date
Line 2: time
Line 3: weather
Line 4+: events
	
Events are added from lines 4 onwards. They must be formatted thusly:

3:Your event here
7:Another Future Event
30:A distant Future Event
...and so on.

Events do not have to be in order, but the program doesn't recognize 
when an event shares its date with another.  Good book-keeping will 
help to ensure that all of your events come to pass. If you want 
multiple events to fall on the same day then my suggestion for that 
looks something like:

4:A goblin ska band is performing in town, The necromancer discovers poetry.

When your starting file is prepared it will look something like this:

1
5
rainy
2:A strange traveller arrives
4:Bizarre creatures begin showing up
5:A state of emergency is declared
40:Apocalyptic events transpire
0

The '0' at the end is a floating tracker, ensure that it's left on it's own line at the bottom 
of your list.

IMPORTANT: Write at least three events, otherwise your first event may not appear.
The program will continue to run.

Best practice is to keep your events brief, if they're too long the text may 
exceed the width of the window making it difficult to read.
------------------------------
TIME:

Time advances by hourly increments. If the time exceeds 24h, you will move into the next day. 
Be aware that there isn't currently a way of reversing time, so be deliberate in your input.
The current world clock is based on Earth time and in future versions there will be an option 
to change this scaling to fit different fantasy timescales.
Additionally, I would like to implement changing seasons in the future designated 
by sections of a user-defined year length. This will include changing temperatures and 
weather patterns.
------------------------------
EVENTS: (namely adding them in-application)

Some of the best ideas come in the moment, you are able to add events while the program is running.
You are able to add new events while using ENCOUNTr by typing 'event'. This will prompt you 
for the details of the event, followed by the day you want the event to come on.
For the sake of convenience, there is a projection of future events 7 days out from the current
date so that they don't sneak up on you. 

------------------------------
EXIT:

The section of the README so important I'm writing it twice: Use 'exit' to close ENCOUNTr, you
WILL lose your progress otherwise. This application will save your progress provided you
respect this aspect of it. 
