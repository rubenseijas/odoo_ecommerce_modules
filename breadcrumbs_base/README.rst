.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
   :alt: License: AGPL-3
   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html

=======================
Breadcrumbs base module
=======================

Friendly breadcrumbs for eCommerce
----------------------------------

This module adds friendly multi-level breadcrumbs for your WEB.

The Breadcrumbs generator is available to call in any template:

::

    <t t-call="breadcrumbs_base.bcb_main_wrap"/>

Moreover, this module adds parent_id field to website.page model. This allows to add parent page for static pages.

    **Attention!**

    This module don't have templates for front-end part of website.

    For correct front-end functionality you need to install additional module **breadcrumbs_base_tmp**.

Author
------

Developer: Comunitea, info@comunitea.com

Contributors
~~~~~~~~~~~~

* Comunitea
* Pavel Smirnov, pavel@comunitea.com
* Rubén Seijas, ruben@comunitea.com

Maintainer
~~~~~~~~~~

This module is maintained by the Comunitea http://www.comunitea.com.

Disclaimer of Warranties
------------------------

    **Attention!**

    We provide this module as is, and we make no promises or guarantees about this correct working.

Comunitea provides this application without warranty of any kind.

Comunitea does not warrant that the module will meet your requirements;
that the current application will be uninterrupted, timely, secure, or error-free or that any defects or errors will be corrected.
