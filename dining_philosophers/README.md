# Dining Philosophers

This solution avoids deadlock by never waiting for a fork while having one in hand. If a philosopher acquires one fork but can't acquire the second, he releases the first fork before waiting to acquire the other (which then becomes the first fork acquired).

## Requirements

- Install python3

### Running

* Run command python3 dining_philosophers.py
* It may not complete for a number of minutes, without the user using a Keyboard Interrupt (such as CTRL-C or CTRL-Z). Run it without interrupting for a while and see things are not going as planned.


