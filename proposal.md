# AG&ARP Research: Artistic Process

## Repository
<Link to your project's public GitHub respository>
https://github.com/SaraUribeR/Uribe_pfda_final_project_proposal.git


## Description
I am a researcher at CG&ARP, a group focused on projects in computer graphics, animation, and interactive techniques. My work centers on the Artistic Process Project, which investigates how artist make digital art across software enviroments like Adobe Photoshop, Clip Studio Paint, and Krita. Our current objective is trying to figure out a method we can use code to track and analyze the digital process of artist. During my reasearch I found an open-source GitHub repository that contains code for a timer in photoshop; however, it is currently limited to macOS, while I use windows. My goal is to is to expand and adapt this existing code to build a version that can help the research being done in CG&ARP. 

## Features
- Updating the Clock Visual
	- Styling the way the clock looks in the terminal.
- Making the code work on Windows
	- Currently the code only works for macOS, want it to be able to work on both, windows and macOS.
- Parsing History Logs and Claculating Total PSD Time.
	- I want the code to read a Photoshop history log, then adding a aspecific time to every action made. I also want it to add the toal amount of time spent working on the PSD file to the log file.

## Challenges
- Cross-Platform Scripting & Refactoring
- ExtendScript & Adobe CEP/JSX Development
- Log Parsing & Data Serialization

## Outcomes
Ideal Outcome:
- The ideal outcome is for me to be able to get a file with specific actions and a time record next to them when working on a PSD file

Minimal Viable Outcome:
- Be able to make the timer work on Windows and have at least a file conected to the Photoshop History Log. 

## Milestones

- Week 1
  1. Identify the exact lines that makes the code crash when running on windows
  2. Try to make it work on windows

- Week 2
  1. Make an ExtendScript function to find, open and use the data inside a History Log file.
  2. Make a loop to iterate through every action being made without crashing

- Week N (Final)
  1. Append a real time timestamp next to each history log action
  2. Test that it works on windows and macOS
