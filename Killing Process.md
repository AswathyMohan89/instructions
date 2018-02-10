#### <u>For rerunning app in 127.0.0.1:5000 when application doesnot reloads in Chrome</u>



1. open cmd and do :`netstat -ano | findstr :<portno>`
![finding_ports](finding_ports.png)
2. do `TASKKILL /?` to get option available for killing
3. do `TASKKILL /PID <process id> / F`  . F - forcefully quits the process.
![killing](killing.png)

