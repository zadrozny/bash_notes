# CRON NOTES

* \* * * * * : minute hour day month year

* confirm time on machine with `date`. Many servers use UTC. 

* If using cron to run a Python process, first confirm the script is working by testing it manually. 

* Confirm the #! path is correct by testing the script with ./script

* Syntax to run a job every 5 minutes: */5 * * * *