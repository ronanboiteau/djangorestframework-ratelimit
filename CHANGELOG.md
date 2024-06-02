# Changelog

## 1.0.0 - 2024-06-03

This version includes [django-ratelimit](https://github.com/jsocol/django-ratelimit) v4.1.0

- Add support rate limiting on the key `data` for use with Django REST Framework's [`Request.data`](https://www.django-rest-framework.org/api-guide/requests/#data)
- Fix duplicated option issue in `tox.ini`
