Moodle Stripe Enrollment Plugin [enrol_stripepay]
=======================
* Maintained by: Zach Washburn
* Copyright: (c) 2016 zPivot, Zach Washburn
* License: [GNU GENERAL PUBLIC LICENSE](LICENSE)
* Contributors:  2015 Dualcube, Arkaprava Midya, Parthajeet Chakraborty

_*Credit goes to Dualcube for the initial work on which this is based_

Description
===========
This plugin helps admins and webmasters use Stripe as the payment gateway. Stripe is one of the popular payment gateways. This plugin has all the settings for development as well as for production usage. It is easy to install, setup and effective.

_Added features include:_
* Username and email saved in stripe transaction details
* Full course name and site logo on stripe checkout modal popup
* Ability to set custom stripe transaction statement descriptor for each course


Installation
============
1. Login to your moodle site as an “admin user” and follow the steps.
2. Upload the zip package from Site administration > Plugins > Install plugins. Choose Plugin type 'Enrolment method (enrol)'. Upload the ZIP package, check the acknowledgement and install.
3. Go to Enrolments > Manage enrol plugins > Enable 'Stripe' from list
4. Click 'Settings' which will lead to the settings page of the plugin
5. Provide merchant credentials for Stripe. Note that, you will get all the details from your merchant account. Now select the checkbox as per requirement. Save the settings.
6. Select any course from course listing page.
7. Go to Course administration > Users > Enrolment methods > Add method 'Stripe' from the dropdown. Set 'Custom instance name', 'Enrol cost' etc and add the method.
8. This completes all the steps from the administrator end. Now registered users can login to the Moodle site and view the course after a successful payment.


Requirements
------------
* Moodle 2.8, 2.9 or 3.0
* Stripe account


How to create Stripe account
--------------
1. Create account at https://stripe.com.
2. Complete your merchant profile details from https://dashboard.stripe.com/account.
3. Now set up secret key and publishers key at https://dashboard.stripe.com/account/apikeys.
4. For test mode use test api keys and for live mode use live api keys.
5. Now you are done with merchant account set up.


Useful links
============
* Moodle Forum: [https://moodle.org/course](https://moodle.org/course)
* Moodle Plugins Directory:  [https://moodle.org/plugins](https://moodle.org/plugins)
* Stripe API: [https://stripe.com/docs/api?lang=php#intro](https://stripe.com/docs/api?lang=php#intro)


Release history
===============
* **v1.0:** 2016-05-05




