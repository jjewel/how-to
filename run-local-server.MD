#How to run a local server for testing web apps
$cd /path/to/directory/

#if http-server is not already installed globally
$npm install -g http-server

#call this command in the directory of your web app
$http-server

#your server should now be running locally
#Ctrl-C to exit


#if you have caching or reloading issues try the following
$http-server -c-1

#if that doesnt work try the browser-sync package
$npm install -g browser-sync

$browser-sync start --server -f

