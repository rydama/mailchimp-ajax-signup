mailchimp-ajax-signup
=====================

**UPDATE: the MailChimp “Classic” embed form now supports inline/ajax submission without a redirect.
So, you probably don't need this. Maybe only if you really want to customize.**


An example mailchimp signup form, without redirects.

To use the example:

* Download ajax-subscribe.html
* Replace the form action url with your own from the MailChimp supplied embed code
* Within the action url, replace "subscribe/post" with "subscribe/post-json"
* Be sure the action url starts with `http://`. If it doesn't, the form will hang when testing the html as a local file in your browser.
* Open the html file in a browser on your local machine
