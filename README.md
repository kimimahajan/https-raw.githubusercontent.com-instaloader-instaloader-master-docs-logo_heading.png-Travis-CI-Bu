.. image:: https://raw.githubusercontent.com/instaloader/instaloader/master/docs/logo_heading.png

.. badges-start

|travis| |pypi| |pyversion| |license| |aur| |contributors| |downloads| |saythanks|

.. |travis| image:: https://img.shields.io/travis/instaloader/instaloader/master.svg
   :alt: Travis-CI Build Status
   :target: https://travis-ci.org/instaloader/instaloader

.. |pypi| image:: https://img.shields.io/pypi/v/instaloader.svg
   :alt: Instaloader PyPI Project Page
   :target: https://pypi.org/project/instaloader/

.. |license| image:: https://img.shields.io/github/license/instaloader/instaloader.svg
   :alt: MIT License
   :target: https://github.com/instaloader/instaloader/blob/master/LICENSE

.. |pyversion| image:: https://img.shields.io/pypi/pyversions/instaloader.svg
   :alt: Supported Python Versions

.. |contributors| image:: https://img.shields.io/github/contributors/instaloader/instaloader.svg
   :alt: Contributor Count
   :target: https://github.com/instaloader/instaloader/graphs/contributors

.. |saythanks| image:: https://img.shields.io/badge/Say%20Thanks-!-ff7efd.svg
   :alt: Say Thanks!
   :target: https://saythanks.io/to/aandergr

.. |aur| image:: https://img.shields.io/aur/version/instaloader.svg
   :alt: Arch User Repository Package
   :target: https://aur.archlinux.org/packages/instaloader/

.. |downloads| image:: https://img.shields.io/pypi/dm/instaloader.svg
   :alt: PyPI Download Count

.. badges-end

::

    $ pip3 install instaloader

    $ instaloader profile [profile ...]

**Instaloader**

- downloads **public and private profiles, hashtags, user stories,
  feeds and saved media**,

- downloads **comments, geotags and captions** of each post,

- automatically **detects profile name changes** and renames the target
  directory accordingly,

- allows **fine-grained customization** of filters and where to store
  downloaded media.

::

    instaloader [--comments] [--geotags] [--stories] [--highlights] [--tagged]
                [--login YOUR-USERNAME] [--fast-update]
                profile | "#hashtag" | :stories | :feed | :saved

`Instaloader Documentation <https://instaloader.github.io/>`__


How to Automatically Download Pictures and Videos from Instagram
-----------------------------------------------------

To **download all pictures and videos from a profile**, as well as the
**profile picture**, run:

::

    instaloader profile [profile ...]

where ``profile`` is the name of a profile you want to download. Instead of specifying only one profile, you can also specify a list of profiles.

To later **update your local copies** of those profiles, you can run:

::

    instaloader --fast-update profile [profile ...]

If ``--fast-update`` is specified, Instaloader stops when it reaches the first picture that has already been downloaded. When updating profiles, Instaloader automatically detects profile name changes and renames the target directory accordingly.

Instaloader can also **download private profiles**. To do so, run it with:

::

    instaloader --login=your_username profile [profile ...]

When you log in, Instaloader **stores the session cookies** in a file in your temporary directory, which are reused the next time ``--login`` is specified. This allows you to download private profiles non-interactively when you already have a valid session cookie file.

`Instaloader Documentation <https://instaloader.github.io/basic-usage.html>`__


Disclaimer
----------

.. disclaimer-start

Instaloader is in no way affiliated with, authorized, maintained or endorsed by Instagram or any of its affiliates or
subsidiaries. This is an independent and unofficial project. Use at your own risk.

Instaloader is licensed under an MIT license. Refer to ``LICENSE`` file for more information.

.. disclaimer-end

Contributing
------------

As an open source project, Instaloader heavily depends on the contributions from
its community. See
`contributing <https://instaloader.github.io/contributing.html>`__
for how you may help Instaloader to become an even greater tool.

It is a pleasure for us to share our Instaloader to the world, and we are proud
to have attracted such an active and motivating community, with so many users
who share their suggestions and ideas with us. Buying a community-sponsored beer
or coffee from time to time is very likely to further raise our passion for the
development of Instaloader.

| For Donations, we provide a PayPal.Me link and a Bitcoin address.
|  PayPal: `PayPal.me/aandergr <https://www.paypal.me/aandergr>`__
|  BTC: 1Nst4LoadeYzrKjJ1DX9CpbLXBYE9RKLwY
