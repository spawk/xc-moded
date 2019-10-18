XC-Moded


Step 1:
Installation
1. With putty login to your server root, then enter this code.

apt-get update && apt-get upgrade -y && apt-get install lsb-release nscd curl php5 php5-mysql php5-cli php5-curl unzip -y && apt-get install php5-mcrypt && php5enmod mcrypt

2. Download and Install the Script, copy and paste:
wget https://github.com/spawk/xc-moded/blob/master/install.sh

3. Set the permissions (copy and paste)
Apache config:
chmod 777 xtream-codes.sh

4. Start the installation of the Script
Bash:
./xtream-codes.sh

5. Questions about updates all with Y confirm.

6. When requesting license from xtream panel, open winscp or other similar program and go to the folder located in
[
var/www/html/modules/servers/licensig] and edit the verify.php folder, and then I followed her <? php will paste this
Bash:
// If U Want Change Licenses Here, From Bubi1, 2, 3, etc. Insert Ur Name
$ Licenses = array ('bubi1');
7. back to putty license [bubi1]

8. Fill the database password

9. Fill the port

10. Fill the panel password

11. Rename the Server

Xtream codes 1.60 panel is installed
To go to the panel [ server ip: port you chose

Load Balancer Working.
