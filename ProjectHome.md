# ABOUT #
Use Django to provide SAML 2.0 assertions that can be consumed by SAML 2.0 Service Providers, including other Django sites that use the django-saml2-sp app @ http://code.google.com/p/django-saml2-sp/

Read more about the Security Assertion Markup Language version 2.0 here:
http://en.wikipedia.org/wiki/SAML_2.0

NOTE: This is targeted for Django 1.2.1. For other versions, YMMV.

## Currently Supported Service Points ##
As of release 0.1, these service points are supported:
  * **SalesForce.com** (and work-alikes that use the HTTP-POST profile)
  * **Google Apps** (and work-alikes that use the HTTP-GET profile)
  * extension to other service points is possible; do it yourself or hire one of our project developers

For more details, see the 'doc' folder in the source.

## Acknowledgments, Installation, and Developer Docs ##
Documents are maintained in 'doc' folder in the source code.


Run the demo sponsored by [Anderson Innovative, LLC](http://www.andersoninnovative.com) at https://spdemo.andersoninnovative.com/. The demo is running code under tag "demo2".