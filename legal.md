---
layout: page
title: Privacy Policy
background: grey
---

<div class="col-lg-12 text-center">
	<h2 class="section-heading text-uppercase">Privacy Policy</h2>
</div>




{% if site.analytics.google %}

Automatically Collected (Google Analytics):

When you visit the Site, we automatically receive information about your device from your browser, such as your IP address. As you browse the Site, we also collect information about how you interact with the Site. We refer to this automatically-collected information as “Device Information”.

We collect Device Information using cookies. “Cookies” are data files that are placed on your device. For more information about cookies and how to disable them, visit http://www.allaboutcookies.org.

We do this using Google Analytics: <https://www.google.com/intl/en/policies/privacy/>.

You can opt-out of Google Analytics here: <https://tools.google.com/dlpage/gaoptout>.

{% else %}


<br>
We do not collect any data about you or use any cookies.

{% endif %}


We may update this privacy policy from time to time for personal, operational, legal, or regulatory reasons.


For more information about our privacy practices or if you have questions, please contact us by email at <a href="mailto:{{ site.email }}">{{ site.email }}</a>.

<br>
<div class="container">
  <div class="row">
      <a class="quackdoctor-link" data-toggle="modal" href="#q1">
       <div class="text-uppercase">{{ site.data.sitetext[site.locale].quackdoctor.ptitle | default: "Terms and Conditions" }}</div>
      </a>
  </div>
</div>
{% include qmodals.html %}
<br>