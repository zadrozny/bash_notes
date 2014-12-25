# CRON NOTES

* \* * * * * : minute hour day month year

* confirm time on machine with `date`. Many servers use UTC. 

* If using cron to run a Python process, first confirm the script is working by testing it manually. 

* Confirm the #! path is correct by testing the script with ./script

* Syntax to run a job every 5 minutes: */5 * * * *

* Cron jobs do not have the environment variables that your login shell does.  Usually when a cron job works on the command line, but not in the crontab, it is missing an environment variable.  You will need to set the needed environment variables when the cron job executes. See:  http://stackoverflow.com/questions/2229825/where-can-i-set-environment-variables-that-crontab-will-use