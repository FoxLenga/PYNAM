# Python Week Of Code, Namibia 2019

https://travis-ci.org/ is an online service
that's helps you test Django.

## Task for Instructor

1. Create a file `.travis.yml` with

   ```
   language: python

   python:
     - "3.6"
     - "3.7"

   env:
     - DJANGO_VERSION=2.2

   install:
     - pip install django==$DJANGO_VERSION

   script:
     - "python manage.py test"
```
2. Push your code to GitHub.
3. Visit https://travis-ci.org/ and sign in with your GitHub account.
4. Enable the continuous integration for your repository.

## Tasks for Learners

None.