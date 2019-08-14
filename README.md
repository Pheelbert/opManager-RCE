# opManager-RCE
DISCLAIMER: I don't condone the use of the script for anything other than legitimate security testing purposes. 

Python script that utilizes opManager's "Workflow" feature to execute arbritrary commands on any managed device (Authenticated).

This script has been tested against opManager version `12.3.150`, though it should work on most versions, deeming the API hasn't been radically changed. Tests have only been done in Windows environments; I will continue testing to make sure the script works in Linux environments as well.

Note that the current version has issues running commands with quotes in them. 
