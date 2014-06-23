#PaD Teemax Tool

A tool for PaD players to aid in powering up their teams, this tool, given a set of monsters and an amount of xp, spits out the most efficient monster in the list stat wise to feed to. 

The name is a play on team and max based on League of Legends' "Teemo" champion.

##Features

The tool will feature several ways to pull monsters including:

- Manual Entry of Monster ID
- Pull from user's entire padherder
- Pull from a specific team on the user's padherder

By default, the tool will assume xp is neutral, but the tool can be set to on-color xp before OR after feeding. So, for example, the user could say:

- 100,000 xp neutral
- 100,000 dark xp before feeding
- 100,000 light xp after feeding
- *Possible, not yet decided* Enter common fodder monsters and xp for feeding is calculated and then inputted

##Language and User Access

The tool would be written in JavaScript, with HTML and CSS so the user can see what they are doing. It would be hosted on Github, with link to the source code as well as bug/suggestion reports. Any user should be able to access it with a modern browser, although Chrome will be the only officially supported browser. *INTERNET EXPLORER WILL BE IGNORED*.

##Tool Algorithm and Production Plan
Basic Algorithm for the actual tool portion, will be expanded upon

	Step 1, Ask the user in which way they will input the set of monsters they'd like to use
	Step 2, If monster data is already in local storage, retrieve it, otherwise pull it from https://www.padherder.com/api/monsters , add it to local storage, and when the operation is complete, let the user know and then move to step 3
	Step 3, Depending on what the user chose in step 1, they enter the monsters now. When they are done, they hit a butan and the tool does its magic on the monsters in the database they specified
	Step 4, The tool outputs which monster would be most effective to feed given their inputs, display button at end that allows user to try again.
	Step 5, If the user pressed to try again, go back to 1

Fancy Graphics Shit:

- Use Code or Web Design software to produce a nice looking interface for the user

##References

- [CDeLorme](http://www.github.com/cdelorme)
- [HTMLDog](http://www.htmldog.com) JavaScript Tutorials

