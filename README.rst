# Django Two-Factor Authentication

[![Jazzband](https://jazzband.co/static/img/badge.svg)](https://jazzband.co/)
[![Build Status](https://github.com/jazzband/django-two-factor-auth/workflows/build/badge.svg?branch=master)](https://github.com/jazzband/django-two-factor-auth/actions)
[![Test Coverage](https://codecov.io/gh/jazzband/django-two-factor-auth/branch/master/graph/badge.svg)](https://codecov.io/gh/jazzband/django-two-factor-auth)
[![PyPI](https://badge.fury.io/py/django-two-factor-auth.svg)](https://pypi.python.org/pypi/django-two-factor-auth)

## Introduction

Django Two-Factor Authentication provides complete two-factor authentication for Django. It is built on top of the one-time password framework `django-otp` and Django's built-in authentication framework `django.contrib.auth`, ensuring easy integration into most Django projects. Inspired by Google's Two-Step Authentication, it offers users multiple authentication methods including call, text messages (SMS), token generator apps like Google Authenticator, or a YubiKey hardware token generator (optional).

If you encounter any issues, please file an issue on GitHub or contribute to the project by forking the repository and sending pull requests. The package is translated into multiple languages including English and Dutch. Feel free to contribute in your own language using Transifex.

Test drive the features of this app through the [example app](https://github.com/jazzband/django-two-factor-auth/tree/master/example), which demonstrates most functionalities except the Twilio integration. The example app also incorporates `django-user-sessions` for enhanced account security control over `django.contrib.sessions`.

## Compatibility

This package is compatible with supported Django and Python versions, including 3.2, 4.0, 4.1, and 4.2 on Python 3.8, 3.9, 3.10, and 3.11. Comprehensive documentation is available at [readthedocs.io](https://django-two-factor-auth.readthedocs.io/en/stable/index.html).

## Installation

Refer to the [installation instructions](https://django-two-factor-auth.readthedocs.io/en/stable/installation.html) in the documentation.

## Getting Help

For general questions regarding this package, visit [Stack Overflow](https://stackoverflow.com/questions/tagged/django-two-factor-auth). If you suspect an issue with the package, check if it's already listed (open or closed) and file an issue if necessary.

## Contribution

Read the [contribution guidelines](https://github.com/jazzband/django-two-factor-auth/blob/master/CONTRIBUTING.rst) to contribute effectively.

## See Also

Explore `django-user-sessions` for Django sessions with a foreign key to the user, also included in the [example app](https://github.com/jazzband/django-two-factor-auth/tree/master/example).

## License

The project is licensed under the MIT license.
