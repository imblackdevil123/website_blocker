# website_blocker
redirects website url to localhost ip.

#program to redirect the certain url to localhost/n
#hosts file contains url and corresponding ip for fast retrival of ip/n
mac/linux ---> etc/hosts /n
windows ----->C:\Windows\System32\drivers\etc\hosts /n
#we can append lines of text in hosts file for ip and url
 
#this host file can only be modified by admin

#to run python in background when script double clicked without popup,replace py extension to pyw extension
#to run the script or program all time sys starts
#go to tack scheduler
#go to create task
#add task (google if want more info)
#go to action and add .pyw(to run background) file
#in unix (linux or mac) based sys to run program when sys start use cron service 
#sudo crontab -e command
#add @root python3 pathtopyfiletorun
