## ERPNext: Open Source, Web Based ERP

ERPNext is an open source, web based ERP ideal for small and medium businesses. It is a feature rich app that covers accounting, inventory, sales (CRM), purchasing, projects, hrms (payroll), support and much more. Has a built-in report builder and form builder

[Checkout our code on github](https://github.com/webnotes/erpnext)

ERPNext is built on [WNFramework - A full stack web app framework in Python and JS](https://github.com/webnotes/wnframwork)

### Download

<a href="http://erpnext.org/erpnext-1.0.0.tar.gz" softlink="false">Download the latest source (erpnext-1.0.0.tar.gz)</a>

### Pre-requisites

ERP Next has a web based client. Our install script currently runs on Linux (and Mac OSX). It should not be too hard to set it up on Windows (though we have not tried it)

Pre-requisites:

	MySQL
	Python (2.6 or above)
	Python-MySQL Connector (MySQLdb)
	Python libs: 
		datetime
		pytz


### Install instructions

Download the latest ERPNext package.

Simple Instructions:

	tar xzf erpnext-1.0.0.tar.gz
	cd erpnext
	sudo python install.py
	sudo apachectl restart (or equivalent)
	
- Start the browser at http://localhost:8080/
	
- Username: Administrator
- Password: admin
	

### Explanation

1. Enter the database name and password (no blank) for installation
2. Enter your root database password (so that the script can create the db)
3. The script will drop an apache configuration file called "erpnext.conf" with the erpnext folder as the document root. It will run a virtual host on the port specified in install_settings.py


### I am new to Linux!

If you are a Linux newbie. Here are some tips to get your started:

1. Install A Nice Linux Distro on your machine ([Ubuntu](http://www.ubuntu.com))
2. Open the terminal: Accessories -> Terminal
3. Install the prerequisites using apt-get / yum:
sudo apt-get install python-mysqldb

Sample installing pre-requisites on Ubuntu:

	sudo apt-get install apache2
	sudo apt-get install mysql-server
	sudo apt-get install python-mysqldb
	sudo apt-get install python-setuptools
	easy_install datetime
	easy_install pytz


### Questions / Forum

- [Techincal Forum (Google Groups)](http://groups.google.com/group/wnframework)
- [ERP Related (Google Groups)](http://groups.google.com/group/erpnext-user-forum)


### Bug Reports

- [File an issue at Github](https://github.com/webnotes/erpnext/issues)


### License

- ERPNext: [GNU General Public License](http://www.gnu.org/copyleft/gpl.html)
- WNFramework: [MIT License](http://www.opensource.org/licenses/mit-license.php)

### Commercial

If you want to use this as a hosted (Software-as-a-service / Cloud) service, register at our commercial offering at [ERPNext.com](https://erpnext.com)


### Donate

This app is a result of many years of labour. If you feel you have benefitted by using this application, please send us a donation so that we know you love us and want us to keep improving this app.

<form action="https://www.paypal.com/cgi-bin/webscr" method="post">
<input type="hidden" name="cmd" value="_donations">
<input type="hidden" name="business" value="rmehta@gmail.com">
<input type="hidden" name="lc" value="US">
<input type="hidden" name="item_name" value="Web Notes Technologies Pvt Ltd">
<input type="hidden" name="item_number" value="erpnext">
<input type="hidden" name="no_note" value="0">
<input type="hidden" name="currency_code" value="USD">
<input type="hidden" name="bn" value="PP-DonationsBF:btn_donateCC_LG.gif:NonHostedGuest">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>



