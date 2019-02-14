# OS-Project
Annie Flora, Amelia Jay, Sophia Prochnow

# Description
Project modifies Linux by modifying the command line call w, which shows who is logged into the server, when they logged in, how long they've been logged in for, and what they're currently doing. The modification will be to first clean up the given output of the w command, since it is not very visually pleasing. Then, the lookback time will be increased from 30 days to 60 days, and finally, the command will now also output the last 3 used programs instead of only 1.

# Rationale
The w command is not very clear when reading directly from the output on the terminal. It does not easily give the user what they're looking for and also does not provide enough information that the user could possibly want. This modification will make the w call easier to understand while also providing more of a history of what the user has been working on.

# Modules Affected
The w command will be modified mainly, along with the history command in order for the w command to see the extensive list of what the user has been working on.
