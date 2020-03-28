# php-gps-locator

https://www.techalyst.com/posts/php-and-laravel-receiving-gps-tracker-data-to-specific-tcpip-port

Save this script in a file called, say "gps.php", and place it along with the SocketServer.class.php into same folder, access the directory in command line,
make the file executable ("chmod a+x gps.php")
and run "php gps.php" from command line.

In gps.php this line:$server = new SocketServer("192.168.1.6",31337); You want to change the ip-address there to reflect the ip-address of your server.  The port number (31337) is arbitrary and can be anything you want.
