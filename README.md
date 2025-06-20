# Education Video Platform

This repository provides a simple Django-based example for delivering
subscription-based educational videos. Private YouTube links are embedded
in course pages and access is restricted to authenticated subscribers.

## Features

- Django project with a `Course` model containing a private YouTube URL.
- Basic subscription model that can be extended with payment gateways
  such as Stripe or PayPal.
- Example template showing how to embed the private YouTube videos for
  logged-in users.

## Getting Started


1. Ensure Python 3 is installed on your system.
   Create and activate a virtual environment::

       python3 -m venv venv
       source venv/bin/activate

   Install the project requirements::

       pip install -r requirements.txt
=======
1. Install Python 3 and Django::

       pip install django

