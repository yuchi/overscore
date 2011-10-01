
        /‾‾‾‾\___/‾‾‾‾\
    /‾‾|     /‾‾‾\     |
        \___/     \___/


Overscore.js
============

Underscore.js for hipsters.

Why?
----

In Underscore.js only common patterns make it into the library. This is
mainly to ensure the quality and stability of the implementation.

This conflict with the *exuberance* of users, who often propose some different
implementation, considering the actual ones not enough good, performant, feature
rich.

But the administrators of Underscore.js cannot put in the trunk something that's
not enough *well-established* and *known*. In one word: **Mainstream**.

Using *Overscore.js* you will be able to say:

* I was using this pattern way before it made into Underscore!
* I used this feature before everyone ever know it exists.
* I use only implementations that no one else uses.

..forget the last one.

Who?
----

Actually the idea came out in a simple discussion on an Underscore.js pull
request for the implementation of a map versione of `_.map`. Jeremy Ashkenas
(@jashkenas) said the use was too less mainstream for Underscore, so the pun about
hipsters was quite obvious. Michael Mahemoff (@mahemoff) made a pun over the pun,
proposing *Overscore*. @jashkenas officialized the project with a `+1`! (This not
really official, but we can pretend it is, ok?)

You can read the discussion [here][1]

[1]: https://github.com/documentcloud/underscore/issues/220#issuecomment-2257448

How?
----

I have some ideas, like:

> Every feature has its folder, with tests and performance
> tests. Every new implementation is named after the feature, with an incremental
> number to differentiate them. A little builder builds a single script ready to be
> used. Every implementation should have some documentation, describing the
> authors, and the why/how.

I'm thinking about using sub-repos, but I'm not a git-wizard, so I'm waiting some
feedback.

When?
-----

Now?
