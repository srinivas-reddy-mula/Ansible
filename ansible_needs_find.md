##  Finding requirements of infrastructural needs

* 1.Identify servers (__infrastructural needs__) for your Environment
* 2.Identify configurations (Software & Deployments) on each Server
    * 2.a) Ensure all the steps for the configuration are Documented












__*Problems*__ :
1.  ##  by using shell script 
#####  Shell script depends upon guy who implementing 
* one guy will do some manner

* other guy will do somehow diffrently

* *In shell you have to inform what and how*
## __Example:__
    sudo apt-get update && sudo apt-get install nginx -y
*__problem from shell script will be overcome by using configuration Management__*

2.  ## By using configuration Management
     * you will say what you want

     ## __Example:__
        i want update packages and ensure nginx is installed
