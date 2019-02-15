# OS-Project
Annie Flora, Amelia Jay, Sophia Prochnow

# Description
Our project modifies Linux by changing the command line call *w*, which shows who is logged into the server, when they logged in, how long they've been logged in for, and what they're currently doing. The modification will first clean up the given output of the *w* command, since it is not very visually pleasing (color code and spacing). Then, we will have the command also output the last 3 used programs instead of only the current.

![alt text](https://github.com/stprochnow64/OS-Project/blob/master/Screen%20Shot%202019-02-14%20at%201.43.35%20PM.jpg)

# Rationale
The *w* command is not very clear when reading directly from the output on the terminal. It does not easily give the user what they're looking for and also does not provide enough information that the user could possibly want. This modification will make the *w* call easier to understand while also providing more of a history of what the user has been working on.

# Modules Affected
The *w* command will be the main module modified, along with the *history* command in order for the *w* command to see the extensive list of what the user has been working on. The modification will also affect *who*, *uptime*, and *ps*.

# Other Possible Ideas
- Include the current time and change it from military time to a 12 hour clock. 
- Color code different output columns. 
- Label each column more clearly so user can better understand the output generated. 
