# txt-fmt
From earthquake alerts to severe weather warnings, the US government
provides a lot of real-time information to anyone who is wants it, often
sent directly to their phone via SMS text messages.  I've signed up for
several services, and one thing I've noticed is that their data is usually
delivered in all uppercase.  That's a problem, because UPPERCASE LOOKS
LIKE YOU'RE SHOUTING.  I sometimes want to re-send an alert to someone,
but I'd prefer to send it in lowercase, and that means I have to retype
the whole thing, because my iPhone doesn't have any of the text tools
that I have on my computer.

That's why I wrote txt-fmt, a simple webapp that lets you perform simple
operations on a bunch of text at once.  The way it works is simple:
In some other app, select and copy a bunch of text.  Start txt-fmt and
paste the text into the edit box.  Press a button, then select and copy
the modified text from the edit box.  Finally, switch to your original
or some other app, and paste the text.  Yes, it's a bit of work, but
it's easier than retyping everything.

Right now, there are just three buttons: "lc" (the reason for writing
the app), "uc" (because it was easy to do), and "rot13" (for aspiring
cryptographers).  But it's easy to add more buttons, and I'm willing to
entertain suggestions from anyone with ideas for things to do.  One thing
on my to-do list is to add a word count field that shows the number of
lines, words and characters in the edit box.  Another is add a way to
do a global search and replace.  Finally, I'd like to add a secondary
edit box, perhaps with permanent storage of text, and a way to do things
like comparisons between the text in the two boxes.  All I need is a
good Javascript library that implements all of the Unix text tools.  :)
