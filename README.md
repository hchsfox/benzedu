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

1. Install Python 3 and Django::

       pip install django

2. Run database migrations::

       ./manage.py migrate

3. Create a superuser for administration::

       ./manage.py createsuperuser

4. Start the development server::

       ./manage.py runserver

5. Log in and add `Course` records in the admin site. Use the YouTube
   share link from your private videos.

This project serves as a foundation. You can integrate a payment system
by tracking active subscriptions and restricting content accordingly.
