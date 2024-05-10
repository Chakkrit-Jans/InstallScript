# <a href="[src/Test.java](https://www.odoo.com/)">Odoo</a> Install Script
This script is based on the install script from Yenthe Van Ginneken (https://github.com/Yenthe666/InstallScript/tree/17.0) but goes a bit further and has been improved. This script will also give you the ability to define an xmlrpc_port in the .conf file that is generated under /etc/ This script can be safely used in a multi-odoo code base server because the default Odoo port is changed BEFORE the Odoo is started.

# Installing Nginx
If you set the parameter INSTALL_NGINX to True you should also configure workers. Without workers you will probably get connection loss issues. Look at the deployment guide from Odoo on how to configure workers.

# Installation procedure
<b>1. Download the script:</b>
## <tab><tab>sudo wget https://raw.githubusercontent.com/Chakkrit-Jans/InstallScript/17.0/odoo_install.sh
