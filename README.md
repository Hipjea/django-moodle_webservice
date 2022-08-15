# Moodle Webservice

A Django reusable app for [Moodle Webservice functions](https://docs.moodle.org/dev/Web_service_API_functions)

## Quick start

1. Add "moodle_webservice" to your INSTALLED_APPS setting like this :

```python
INSTALLED_APPS = [
    ...
    'moodle_webservice',
]
```

## Build

1. Move into django-moodlewebservice

2. Run `python setup.py sdist`

3. Move back into the project directory

4. Install the app `pip install django-moodle_webservice/dist/django-moodle_webservice-1.0.tar.gz`
