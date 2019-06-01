# learningvscode
It's all about visual studio code. I've been using *vscode* for 2 years and totally in love with its flexible environement for web developement. 
# Bug : Copy/Cut from current cursor and paste/replace with selected text in vscode
**Overview**
I usually copy or cut whole line in vscode to copy it to another location or replace with another line. Using mouse to select whole line for copying and paste it with mouse or shortcut key *CTRL+V*, it's time consuming and very awful task to do this. Accidently I found that I can do this by *CTRL+C* OR *CTRL+X* at given cursor and whole line copied to the clipboard. While using regularly, this feature creating problem for me. The problem is the whole line with new line.
**Problem**
Here is the sample for problem
![alt text](https://github.com/mudassar045/bugreporting/raw/master/src/common/images/icon48.png "Buggy Image")
**Solution of the above problem**
When pressing *CTRL+C* OR *CTRL+X*, should select text not whole line with new line character, so when pasted/replaced, only past/replace the text not whole line.
![alt text](https://github.com/mudassar045/bugreporting/raw/master/src/common/images/icon48.png "Solution Image")

# Comparison between VS-Code and Visual Studio
Here in this example gif, you can see that how **VS-Code** behaves
![alt text](https://github.com/mudassar045/bugreporting/first-bug-report-vscode-video.gif "vs code gif")

Here in this example gif clip, you can see that how **Visual Studio** behaves
![alt text](https://github.com/mudassar045/bugreporting/first-bug-report-vs-video.gif "visual studio code")
