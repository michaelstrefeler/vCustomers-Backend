# vCustomers-Backend
RESTful API using the slim framework for PHP with a MySQL database

I'm running the API on XAMPP. To make it work you need to add a vhost and add a host to the hosts file.

## Adding a vhost
If you are using XAMPP go to C:\xampp\apache\conf\extra and edit the httpd-vhosts.conf file. If you aren't using XAMPP go to wherever your apache file is and open the same file.

Uncomment NameVirtualHost *:80 if you haven't already done that and add the following code to your httpd-vhosts.conf file
```
<VirtualHost *:80>
	DocumentRoot "C:/xampp/htdocs/slimapp/public"
	ServerName slimapp
</VirtualHost>
```

## Adding a host
Run Notepad as an administrator(if you don't you won't be able to save it) go to C:\Windows\System32\drivers\etc and open the hosts file. 

Add `127.0.0.1 slimapp` to the file and save it.

You can replace slimapp with whatever you want to call the API.

## Using the API
All you need to do the use the API is run XAMPP and start Apache and MySQL
