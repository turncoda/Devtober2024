# Devtober 2024
Welcome to our efforts in developing a game over the month of Octover. The requirements are loose and mostly self-imposed. The goal is to just work on stuff, and post about it if you want to. As of writing this I have no idea what this game will be, but I'm putting together as much as I can to make sure collaboration can happen. The full gamjam page is here: https://itch.io/jam/devtober-2024

# Instructions for Contributors
It helps if you know how to use git and version control stuff, and helps if you know how to use Godot. I am a newcomer to Godot so I'll be learning as much as I can through this too, so don't worry if you are lost. The point of this project is to learn. IF you are experienced in Godot I welcome you and appreciate you even more, I might be needing your knowledge and advice.

## How to get started in Godot
First download Godot 4.3 https://godotengine.org/download/windows/
It should be the most recent version. There is no "installation" for godot, so you will either have to know where you saved it OR register it under "open as" when you right click project.godot file so that you always open .godot file with the appropriate exe.
On that note, you can download this repository. Once you extract it, I beleive opening "project.godot" with the "Godot_v4.3-stable_win64.exe" file SHOULD open the godot project and give you the appropriate ".godot" folder needed for everything to function. If not, let me know and we can figure something out.

## How to get started in git (version control)
Well you are here, so thats a good start. You can pick whatever git client you like for version control, but if you are unfamiliar I suggest one with a graphic user interface. I personally use GitKraken. You can use Git For Windows or whatever works for you. Version control is its own skill, so we will use it in the simplest form I can think of:

When you get the git repo all set there will be at least a branch called "main". First and foremost make a new "branch" to work on for you. Just name it with "dev-" and then your initals or account name or whatever, just use - instead of spaces. For example I'll be working in "dev-jv". Each time you go to work on something make sure you "checkout" your branch first. Then you can do whatever you want with the project and files. When you want to "save" your work to the repository, you can "commit" it. That will save the state of the project locally on your computer. When you want to save it to the internet, like when you have a finished something or you make your progress for the day, you "push" your commits. When you think everything you have is working correctly you can ask me and I will "merge" your changes into the "main" branch.

The idea is that the "main" branch is the most stable functioning version of the game. Any works in progress will be on our own "dev-" branches. If you like to separate what feature your working on you can have multiple other branches and name them whatever you want. Then you can merge them into your main "dev-" branch when you are ready to test and then share with main.

For example:
I may make a branch "jv-concept-art" to put my art and sketches in there so I have them all backed up and I have a history of changes and etc, and when I want to share, I will "merge" it into the "dev-jv" branch and "push" that code to the online repository. Then I can have another branch like "jv-enemy-controller" or something, and merge and push THAT into jv-dev too. I can then use jv-dev as my sort of staging area to test and make sure all branches I merge in are working correctly together, and merge with the "main" branch when it all works. Its just how I prefer to work, because I can use git to clearly see a history of what I was working on and when it was merged and etc.

If you want to get the changes from the online repository, you'll do a "pull". You can also "merge" the changes in the "main" branch into your own branch to test and work in things others have worked on into your own work. Then when go to merge into main it will be that much easier. I usually do this when I remember because it feels cleaner to work out any merge issues in a separate branch rather than in the main one.

This is a lot for novices to git so just ask if you have questions or if you want to do things another way and I'll try to accomodate you. If you really want, you can send my all the files and I'll merge them in, its just more time and effort on my part. Version control like git is a valuable tool and very worthwhile knowing how to use it though, in just about every job, so I higly suggest getting some familiarity with it.
