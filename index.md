---
layout: col-sidebar
title: OWASP Single Sign-On
tags: owasp sso overview
level: 2
type: tool
pitch: Centralize your decentral logins with the safest and most privacy-oriented Single Sign-On experience. Keep the data where it belongs - in your hands!
---

<!-- rebuild -->

[![OWASP Incubator Project](https://img.shields.io/badge/owasp-incubator%20project-fe7d37.svg](/projects/#div-main)
[![GitHub release](https://img.shields.io/github/v/release/OWASP/SSO_Project.svg)](https://github.com/OWASP/SSO_Project/releases/latest)
[![GitHub stars](https://img.shields.io/github/stars/OWASP/SSO_Project.svg?label=GitHub%20%E2%98%85&style=flat)](https://github.com/OWASP/SSO_Project/stargazers)

OWASP SSO is a NodeJS application that allows a secure-by-default self-hosted SSO experience, 
including phishing-proof two-factor authentication, using state-of-the-art security mechanisms.

## Description

Companies are struggling to properly secure access to their infrastructure, as many teams and projects need to re-implement authentication. 
A change in security policy (eg mandatory two-factor authentication) has difficulties propagating throughout the whole business, 
and the security team has issues bringing many proprietary login systems together for monitoring and reaction.

The solution - of course - is SSO. 
However this field is heavily dominated by a few global players.
A company looking to implement SSO often needs to have the access to all of its company data and its employee data usually managed by one of those large vendors.
This creates privacy and compatibility issues.

OWASP SSO is a solution that can be easily deployed and enforces a secure SSO experience with full control over the data. 
It can authenticate users for different applications using phishing-proof state-of-the-art MFA (FIDO2, client certificates that can integrate with the existing certificate infrastructure of a company, and anti-phishing email confirmation) across all devices, 
allows to centrally log user changes and send them to the SOC team to immediately detect and remediate any attacks, 
allows applications to easily embed secure authentication at different stages (eg an application can do login internally and only send users to the SSO for MFA).

By providing companies the possibility to run their own SSO with the highest standards of security and saving a lot of money on development costs of each project, 
OWASP SSO plans to become the primary choice for enterprises with increased security or privacy requirements.

## Contributors

[![GitHub contributors](https://img.shields.io/github/contributors/OWASP/SSO_Project.svg)](https://github.com/OWASP/SSO_Project/graphs/contributors)

OWASP SSO has been created by
[@JamesCullum](https://mailhide.io/e/Wno7k) and is developed,
maintained and translated by a
[team of volunteers](https://github.com/OWASP/SSO_Project/graphs/contributors).

## Licensing

[![license](https://img.shields.io/github/license/OWASP/SSO_Project.svg)](https://github.com/OWASP/SSO_Project/blob/master/LICENSE)

This program is free software: You can redistribute it and/or modify it
under the terms of the
[GPL License](https://github.com/OWASP/SSO_Project/blob/master/LICENSE).
