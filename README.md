![WIP](https://github.com/EloiStree/EloiStree/blob/master/Images/WIP.png)  

 The current application OMI as UDP port to inject command and value from your third app.  
A udp interpreter hooks can be add to inject your own executor.  
You can use UDP message to send command to your third app.  

Those a present in the app but the documentation is missing.  
Contact me if you want to play around with the tool.  

--------------------------------------


# API

Find information about how to hook as developer to the application(s)

The idea behind Open Macro Input is to let's developer hook to the tool or add functionnality.

In the current version of July 2023 you can hock in two ways.
- Push command to execute on port 2506 (by default)
- Add Regex Interpretor to the app that delegate code to execute based on command format.

You can add your own code in the app by forking the project in Unity3D and rebuild your version.

I would like to add in the future some more:
- LUA obviously
- Python for standalone platform
- dll for window


