---
layout: page
title: Registration
registration_state: open
email: gapdays2020-spring@gapdays.de
---

{% case page.registration_state %}
{% when 'notyet' %}
<p class="message">Registration will be open soon.</p>

{% when 'closed' %}
<p class="message">Registration is closed.</p>

{% when 'open' %}
<p class="message">Registration is open.</p>

To register please send an email to [gapdays2020-spring@gapdays.de](mailto:gapdays2020-spring@gapdays.de) with the following contents.
```
Registration for GAP Days 2020 Spring

Name:
Affiliation:
Date of Arrival:
Date of Departure:
```

<p>
If you have any questions
regarding registration, or in general, feel free to
<a href="mailto:{{page.email}}">contact us via email</a>.
</p>

{% endcase %}