# Django REST Framework Ratelimit

Django REST Framework Ratelimit is a fork of [Django Ratelimit](https://github.com/jsocol/django-ratelimit) that adds support for rate limiting on Django REST Framework's `Request.data`

## Usage

Refer to the [Django Ratelimit v4.1.0 documentation](https://django-ratelimit.readthedocs.io/en/v4.1.0/).

This fork simply adds support for the extra [ratelimit key](https://django-ratelimit.readthedocs.io/en/v4.1.0/keys.html) `data`. Example:

```py
from django_ratelimit.decorators import ratelimit

ratelimit(key="data:username", rate="5/m", method="POST")
```
