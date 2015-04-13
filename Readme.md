# Setting the Environment in OSX

Newer version of OSX have (once again) broken the old mechanisms for
setting environment variables in GUI applications.  This repository
contains two files that can be used to register values for environment
variables.

Modify the `com.xantira.loginscript.plist` file as indicated in the
file and copy it to your `~/Library/LaunchAgents` directory.  Add all
required environment variables to the `setenv.sh` script in the manner
indicated by the commented-out lines, i.e., by calling `launchctl
setenv` with the name and value of the variable as parameters.


