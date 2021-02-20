+++
image = "img/placeholder.png"
showonlyimage = false
title = "A Django Blog Platform"
draft = false
weight = 4
+++

A blogging platform built using Django 2.2, Python 3.6, SQLite 3 and Bootstrap.

Pluggable blog post & search apps, user management, security, Django authentication. Post drafts, saving & editing. Complex lookups.
<!--more-->

- [View Source Code](https://github.com/andybyers21/django-blog-platform)

A blogging platform built using Django 2.2, Python 3.6, SQLite 3 and Bootstrap.

![blog page](/img/django_blog/blog_page.png)

## Features

- Pluggable blog post & search apps.
- Sessions. Login, user management, security, Django authentication.
- Draft post saving & editing (visible only to admin & superusers).
- Complex lookups, search for user, title, content, slug etc…
- Monitor lookups & search queries.
- Static file & Image uploads.
- Forms / model forms.
- URL routing.
- Optimised for speed.

## Logins for testing

- **User**, *username:* test-user *Password:* story011
- **Admin**, *username:* test-staff *Password:* afraid357
- **Superuser**, *username:* test-super *Password:* current912

![code page](/img/django_blog/blog_code.png)


## Admin Pannel

![admin page](/img/django_blog/blog_admin.png)

## Depandancies

|||
|---------------|------------|
autopep8        |   1.5.4
Django          |   2.2
Pillow          |   7.2.0
pip             |   20.2.2
pycodestyle     |   2.6.0
pytz            |   2020.1
setuptools      |   49.6.0
sqlparse        |   0.3.1
toml            |   0.10.1
wheel           |   0.35.1

---

## TO-DO

- [ ] Define Error / 404 page.
- [ ] Refactor & document code.
- [ ] Take out of Debug Mode
- [ ] Host.

---

## Bugs

- [ ] Two Login buttons on Nav before login
- [ ] Add image to an edited post is borken.
- [ ] Update search returns 0 results page, if returns no results - Say your search for … returned no results

