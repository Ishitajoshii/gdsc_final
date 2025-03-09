# gdsc_final
->BOT FEATURES

Command->	Usage-> Example	Function
!chat->	!chat what’s the capital of India->	Chatbot using Gemini AI
!remind->	!remind 30 drink water->	Sets a reminder
!poll->	!poll “fav color” “pink” “blue”->	Creates a poll
!play->	!play <YouTube_URL>->	Plays YouTube audio
!pause->	!pause->	Pauses music
!resume->	!resume->	Resumes music
!stop->	!stop->	Stops music

What I learnt?
1. Basic VSCode
Prior to this , I have only used online web compilers or simple coding shells like idle. Using VSCode was a new experience for me and made me realize how useful it is in comparison as it can be directly integrated with mutliple other platforms including and git and it's also much faster. I learnt how to run, debug and edit a VS Code file.

2. Python code
a. venv
venv is a tool in python used to create a virtual environment wherein certain important and sensitive information can be hidden under another environment and is not uploaded to public repositories like this one. venv was used in my code to hide discord token and the gemini api key. (The gemini api key at the end was used directly in code(because it wasn't wokring otherwise)- which could be a safety precaution- i'm work on fixing that)
The venv folder contains a Scripts folder that has activation scripts that make sure Python uses the virtual environment’s packages, not the system ones.

Syntax: 
[python] python -m venv <name of venv>
[cmd] venv\Scripts\activate #remember to deactivate at end of code


b. Using decorator
decorators are functions that act as extensions to another function without changing the original other function.
the decorator fxn must precede the actual fxn while defining as well as while calling. a decorator is called using @<name_of_decorator>


c. async
async=asynchronous fxn-> usually when a fxn runs on python, it takes up all of the complier's time and space. for async fxns however, other program execution is allowed while an async fxn is being executed. This is useful in the discord bot as if a server has mutiple users calling mutiple requests from the bot- time needs to be managed well.

3. Using terminal, cmd- this was especially time consuming for the music part to employ the ffmpeg file and i learnt basic commands required for individual activities using chatgpt.
