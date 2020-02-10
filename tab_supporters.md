---
title: Supporters
layout:  null
tab: true
order: 2
tags: sso
---

## Project Supporters

> You can attribute your donation to the OWASP SSO project by
> using
> [this link](/donate?reponame=www-project-sso&title=OWASP+SSO)
> or the green "Donate"-button while on any tab of the OWASP SSO
> project page!

Code contributions count as sponsorship - [see details](https://github.com/DefectDojo/django-DefectDojo/blob/master/SPONSORING.md).

### Top Supporters

[![Panasonic Information Systems Company Europe](assets/logos/PISCEU.png)](https://application.job.panasonic.eu/data/ruP0pHQvHrGZJKvL/rc.php?nav=jobsearch&custval12=ite&lang=EN&custval11=PBSEU_GER)

#### All Corporate Supporters

* [Panasonic Information Systems Company Europe](https://application.job.panasonic.eu/data/ruP0pHQvHrGZJKvL/rc.php?nav=jobsearch&custval12=ite&lang=EN&custval11=PBSEU_GER)<sup>(2019-2020)</sup> <!-- Main code contributor -->

#### All Individual Supporters

{% assign individual_supporter = site.data.ow_attributions | uniq %}
{% for supporter in individual_supporter %}
* {{ supporter | strip_html | strip_newlines | strip }}
{% endfor %}
* _You want to appear on this list?_
  [Donate to OWASP here! 🤲](/donate?reponame=www-project-sso&title=OWASP+SSO)

---

_The OWASP Foundation is very grateful for the support by the
individuals and organizations listed. However please note, the OWASP
Foundation is strictly vendor neutral and does not endorse any of its
supporters._
