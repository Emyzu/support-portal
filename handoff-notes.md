# Developer handoff notes

## What I delivered
The final version displays a customer support page that includes the contact information for the support team (email and working hours) as well as a FAQ section.

## How I verified the page
I verified the page by using the visual studio live server plugin. This plugin allowed me to view the page on a localhost port and make sure that all the features were correctly displaying. I also made sure to check that when I pushed a new commit all the files were showing correctly on GitHub.

## Remote change I received
The escalation update was a teammate editing the README.md file to document a change made. To receive the changes made I ran the command git pull --ff-only origin main.

## Git workflow explanation
Git commit only saves the staged changes locally. In order to update the changes to GitHub you need to run git push to the branch you are editing.