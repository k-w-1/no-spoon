# no-spoon

Ah, how I miss the days of `telnet towel.blinkenlights.nl`. While searching for documentation on how to do matrix math in PowerShell, I came across this entirely unrelated but delightful bit of PoSH code, and decided to turn it up a notch.

From a PowerShell window, run `. { iwr -useb https://raw.githubusercontent.com/k-w-1/no-spoon/main/spoon.ps1 } | iex` and enjoy!. Note that it'll adapt to the correct console width/height at start, but doesn't catch resizes, so for full effect you'll want to go fullscreen off the bat :D.

Even works in embedded terminals:
![image](https://github.com/k-w-1/no-spoon/assets/68672040/9cf1b68d-4a4f-4501-8cc0-32b5ba28d169)

As noted in the top of the copy of the script here in this repo, credit to Reddit user [u/Ecrofirt](https://www.reddit.com/user/Ecrofirt/) for the code they posted [here](https://www.reddit.com/r/PowerShell/comments/rlkacf/powershell_matrix_simulator/).
