# PrawlyDetector
A DLL injection detector for bo3. Just testing atm, but can currently detect injected DLL's (which is how the GSC is injected). The testing required from here is whether the DLL can be hidden while still injecting GSC.

# How it works

Run the main.exe file. This will show a list of DLL's attached to the black ops 3 process. Running the test post-injection shows the t7internal.dll

Let me know if there are any cross platform issue's, and please test injection on your system and see if you get the same results that I did.

This was really hastily put together as a proof of concept. I'll probably decompile the dependency so that it can just be one clean executable (it reads the list of DLL's as a csv file wouldyabelieveit).

# DOESN'T WORK! Leaving this here for anyone with similar ideas.
