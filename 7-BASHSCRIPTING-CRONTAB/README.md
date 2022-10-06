# BASH SCRIPTING AND CRONTAB

### This is a simple bash script written by me to test my knowledge on automating tasks using bash scripting and scheduling executions using crontab. 


### This script runs every hour saving my local linux system memory (RAM) usage to a specified file and sends the file to my email at midnight, and starts again the next day 


### This is a copy of my bash script 
!["Bash Script"](/EXERCISE%207/IMAGES/Screenshot%20(167).png "Bash Script")

### This is a copy of my cronjob
!["Cron Job"](/EXERCISE%207/IMAGES/Screenshot%20(166).png "Cron Job")

### This is a sample of the mail I received at midnight containg the file that my memory usage was stored in.
!["Sample Mail"](/EXERCISE%207/IMAGES/Screenshot%20(169).png "Sample Mail")

### This is the content of the file I received which contains the system memory (RAM) usage.
!["Mail Content"](/EXERCISE%207/IMAGES/Screenshot%20(170).png "Mail Content")


### I integrated a 3rd party app with my linux system called Cronitor which monitors my cron job to make sure that my cron jobs are all working fine and alerts me via email in the event that there is an error.

### My system memory usage cron job didnt run 4 different times as a result of my system being offline and I was duly notified by cronitor when my cron job didn't run and also notified when my cron job recovered i.e after my linux system came back online.

### This is my Cronitor dashboard indicating the monitoring of my cron job with 8 executions and 3 alerts as at the time of the taking this screenshot.
!["Cronitor Dashboard"](/EXERCISE%207/IMAGES/Screenshot%20(171).png "Cronitor Dashboard")

### This is a sample of the mail I got from Cronitor indicating that my system memory cron job didn't run on schedule
!["Cronitor Mail"](/EXERCISE%207/IMAGES/Screenshot%20(172).png "Cronitor Mail")

### This is a sample of the mail I got from Cronitor indicating when my system memory cron job recovered and ran on schedule
!["Cronitor Mail"](/EXERCISE%207/IMAGES/Screenshot%20(173).png "Cronitor Mail")