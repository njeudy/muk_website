[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Build Status](https://travis-ci.org/muk-it/muk_website.svg?branch=12.0)](https://travis-ci.org/muk-it/muk_website)
[![codecov](https://codecov.io/gh/muk-it/muk_website/branch/12.0/graph/badge.svg)](https://codecov.io/gh/muk-it/muk_website)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d2a8b92329924cc8a5c1121282341145)](https://www.codacy.com/app/keshrath/muk_website?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=muk-it/muk_website&amp;utm_campaign=Badge_Grade)
[![Demo](https://img.shields.io/badge/demo-Try%20me-243742.svg)](https://demo.mukit.at/)

# MuK Odoo Website Modules

This set of modules offers extension for the website builder.

### Installation

To install this module, you need to:

Download the module and add it to your Odoo addons folder. Afterward,
log on to your Odoo server and go to the Apps menu. Trigger the debug
mode and update the list by clicking on the "Update Apps List" link. Now
install the module by clicking on the install button.

Another way to install this module is via the package management for
Python ([PyPI]).

To install our modules using the package manager make sure
[odoo-autodiscover] is installed correctly. Then open a console and
install the module by entering the following command:

`pip install --extra-index-url https://nexus.mukit.at/repository/odoo/simple <module>`

The module name consists of the Odoo version and the module name, where
underscores are replaced by a dash.

**Module:**

`odoo<version>-addon-<module_name>`

**Example:**

`sudo -H pip3 install --extra-index-url https://nexus.mukit.at/repository/odoo/simple odoo11-addon-muk-utils`

Once the installation has been successfully completed, the app is
already in the correct folder. Log on to your Odoo server and go to the
Apps menu. Trigger the debug mode and update the list by clicking on the
"Update Apps List" link. Now install the module by clicking on the
install button.

You can also view available Apps directly in our [repository] and find a
more detailed installation guide on our [website].

### Upgrade

To upgrade this module, you need to:

Download the module and add it to your Odoo addons folder. Restart the
server and log on to your Odoo server. Select the Apps menu and upgrade
the module by clicking on the upgrade button.

If you installed the module using the "pip" command, you can also update
the module in the same way. Just type the following command into the
console:

`pip install --upgrade --extra-index-url https://nexus.mukit.at/repository/odoo/simple <module>`

When the process is finished, restart your server and update the
application in Odoo, just like you would normally.

  [PyPI]: https://pypi.org/project/pip/
  [odoo-autodiscover]: https://pypi.org/project/odoo-autodiscover/
  [repository]: https://nexus.mukit.at/#browse/browse:odoo
  [website]: https://mukit.at/page/open-source
  [MuK IT]: https://www.mukit.at/
