Interactive Login to Liberta Casa Services
==========================================

==========================
Current Scope and Features
==========================

User Registration
    This is the primary feature for the initial release. Liberta Casa exposes many services via SSO which improves
    end user experience. The hindrances to this are manual intervention being required for sending users the link
    and then telling them to check the email confirmation etc. Also they do need to register it like any old web form.

    One solution to this is the ``KeyCloak`` plugin on the bot but that requires a similar intervention and knowledge of syntax

    This ``Rasa`` based conversational user registration system aims to make this simple for the end user and require less
    intervention by network staff.


=====
Setup
=====

* Set up a virtual environment using ``python3 -m venv venv``
* Clone the repository and install the dependencies using ``pip3 install -r requirements.txt``
