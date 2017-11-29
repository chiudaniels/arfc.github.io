---
layout: manual
title: Getting Software Help from Katy
subtitle: "You have a bug. I am not your only hope."
permalink: /manual/guides/katy/codereq
---

![Googling the Error Message](https://pbs.twimg.com/media/CfFPuvoWwAALmcC.jpg "The most important fake book of our time."){:width="270px"}
![Trying Stuff Until It Works](https://pbs.twimg.com/media/CfSQdwUW8AErog1.jpg:large "Another important fake book on persistence."){:width="270px"}

# Google it

Please don't come to me with a question that can be solved by a Google search 
of the error. Especially if you are a Millenial from the U.S., Google really 
should be in your blood by now. For better google skills, consider 
[powering up your search tactics](http://www.powersearchingwithgoogle.com/course/aps/skills).

Once you google it, of course, try the things you found on google. 

# Stack Overflow

If Google isn't sufficiently refined, or if your code issue isn't extremely 
urgent, consider asking your question on the largest programming bug forum in  
the solar system... [Stack Overflow](http://stackoverflow.com/). Be forewarned: the SO community 
is not always friendly or well-moderated for snark. That said, you can definitely improve your odds of kind 
answers by following [these tips on asking a question 
well.](http://stackoverflow.com/help/how-to-ask).

# Check your environment

There are a lot of ways that your programming environment can make things fail. 

Execute the following commands, and ask yourself whether these values could 
explain your issues:

- echo $PATH
- echo $PYTHONPATH
- echo $LD_LIBRARY_PATH
- echo $DYLD_FALLBACK_LIBRARY_PATH
- which 'insert your program here'
- which python
- which gcc

If you don't know how to interperet these runes, google around to find the 
meaning of these environment variables. Or, read the first chapter of [the 
book](http://physics.codes).

# Debuggers and Profilers

Try to debug with an interactive debugger or find memory errors with a 
profiler.  There is a section on debugging and profiling in [the 
book](http://physics.codes). 

# Minimal Working Example

To get the most out of your Stack Overflow question or your meeting with me, 
you will need to formulate a [Minimal Working 
Example.](http://stackoverflow.com/help/mcve)

Yes, sometimes a minimal working example is hard to create. If that's the case, 
I understand. However, you should still do what you can to document what you 
are trying to do, how you got where you are, how you tried to fix it. I will 
need this information to help you.

# Contact me

If you have tried _everything_ above and nothing has been clarified, then 
should you email me.  The email should include your minimal working example or 
your detailed documentation of the problem (above). I may need a few days to 
look it over (so you may as well also add it to Stack Overflow in case they're 
faster than me.) If I can't help you fix it by email, I'll let you know we 
should meet. If we need to meet, [schedule a 
meeting.](/manual/guides/katy/meeting) 

