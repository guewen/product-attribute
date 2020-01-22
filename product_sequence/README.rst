================
Product Sequence
================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fproduct--attribute-lightgray.png?logo=github
    :target: https://github.com/OCA/product-attribute/tree/13.0/product_sequence
    :alt: OCA/product-attribute
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/product-attribute-13-0/product-attribute-13-0-product_sequence
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/135/13.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

This module allows to associate a sequence to the product reference.
The reference (default code) is unique (SQL constraint) and required.

You can optionally specify different sequences for different product
categories.

**Table of contents**

.. contents::
   :local:

Usage
=====

To specify a different sequence for a product category proceed as follows:

#. Go to the a Product Category form view.
   (**note:** you will need to install Inventory app to be able to access to
   the form view, *Inventory > Configuration > Products > Products Categories*;
   or create a menuitem manually).
#. Fill the *Prefix for Product Internal Reference* as desired.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/135/12.0

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/product-attribute/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/product-attribute/issues/new?body=module:%20product_sequence%0Aversion:%2013.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Zikzakmedia SL
* Sodexis

Contributors
~~~~~~~~~~~~

* Angel Moya <angel.moya@domatix.com>
* Graeme Gellatly <g@o4sb.com>
* Sodexis <dev@sodexis.com>
* Lois Rilo <lois.rilo@eficent.com>
* Sudhir Arya <sudhir@erpharbor.com>
* Alexandre Díaz <alexandre.diaz@tecnativa.com>
* Sergio Teruel <sergio.teruel@tecnativa.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/product-attribute <https://github.com/OCA/product-attribute/tree/13.0/product_sequence>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.