********************
Account US UT Module
********************

The account_us_ut module adds accounts to the account_us_ Tryon_ module that
deal with basic Utah sales and use tax.

- Default taxes and codes support a single place of business.
  
- To support multiple fixed places of business, add corresponding tax groups
  and subcodes to the tax chart for each outlet, with all the associated taxes
  and tax lines that are needed for that location.

- To support sales at multiple non-fixed places of business, contact the owner
  of this module to discuss the creating of an account_us_ut_extended module
  that would include subcodes and associated taxes for each county and city
  code in Utah.

This project is currently alpha-quality and subject to major reconstruction, so
use `at your own risk`_. Feedback is greatly appreciated!

For feedback, questions, or technical support, please `contact us`_ or `file an
issue`_.

.. toctree::
   :maxdepth: 2

   usage
   design

.. _Tryton: https://www.tryton.org
.. _contact us: https://pentandra.com/company/#contact
.. _file an issue: https://github.com/pentandra/account_us_ut/issues
.. _account_us: https://github.com/pentandra/account_us
.. _at your own risk: LICENSE
