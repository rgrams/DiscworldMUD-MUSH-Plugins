# Dead Letter Solver
A MUSHclient plugin for the Discworld MUD.

* Original version written by Ruhsbaar of the Venerable Council of Seers.
* Mostly rewritten by Ross Grams AKA "Tuppy".

## What Does it Do?
This plugin will display the full name and location of your dead letter target whenever you read a letter. 

## Installation
1. Start up the MUSHclient.
2. In the File menu, click "Plugins..."
3. Click the "Add..." button.
4. Locate and open the plugin file: "DeadLetter.xml".
5. Done!

## Changelog

### Version 1.0
"Ross Rewrite"

- Add local and close-by people.
- Remove manual aliases, "sl" and "solveletter".
    - Do it automatically whenever you read a letter!
- Use "Written in scribbled handwriting:" for initial trigger.
- Only ever search for the target's name.
- Stop on the line after "Written in hastily scrawled text:".
    - The "Deliver by <date/time>" line is removed if you log out and log in again.
- Also stop after 8 lines just in case.
- Add a failure message.
- Show scry name in bold instead of between brackets.
- Make variables local instead of global.
- Move duplicated code into a function.
