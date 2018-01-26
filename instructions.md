# How to use git & github.com

## Open a terminal:

	You can do this from your Ubuntu desktop with:

		CTRL + ALT + t

	Or switch to a text TTY with:

		CTRL + ALT + F1/2/3/4/5/6

	Switch back to the graphical TTY with:

		CTRL + ALT + F7

## Make sure git is installed. It should be installed by default but _you never know_..

		which git

	Is it installed? If so, skip this command:

		sudo apt-get install git

## Clone the code from the github.com repository onto your computer:

		git clone https://github.com/AliQuietRiot/learning.git
		cd learning
		ls -a

## Write some radical code!

		touch homework-solution.js
		nano homework-solution.js

## Test it!

		node homework-solution.js

## Push your code back up onto the internet:

	Check which files are untracked:

		git status

	Add untracked files:

		git add 1337code.js n00bcode.js

	Create a new commit:

		git commit

	Submit a push request:

		git push
