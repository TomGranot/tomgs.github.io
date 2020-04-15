## What now?

For now, this only contains a fork of [@evanw](https://github.com/evanw)'s awesome [Finite State Machine Designer](http://madebyevan.com/fsm/) under `/fsm`.

All I did was add an option to export to JSON, and import from JSON.

It works OK, but needs some additional things:

1. Loading more than once does not clear the canvas properly.
2. Loading more than once causes duplications.
3. Logically, it should allow you to download the JSON as a file.
4. Logically, it should allow you to load the JSON by uploading a file.
