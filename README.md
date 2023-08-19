<!-- markdownlint-disable -->
<h1 align="center">
    best-of-django
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome projects. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-130-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/fkromer/best-of-django/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/fkromer/best-of-django?color=green&label=updated"></a>
</p>

This curated list contains 130 awesome open-source projects with a total of 260K stars grouped into 32 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/fkromer/best-of-django/issues/new/choose), submit a [pull request](https://github.com/fkromer/best-of-django/pulls), or directly edit the [projects.yaml](https://github.com/fkromer/best-of-django/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Admin Interface](#admin-interface) _8 projects_
- [Admin Interface Actions](#admin-interface-actions) _4 projects_
- [Admin Interface Filters](#admin-interface-filters) _1 projects_
- [Management Commands](#management-commands) _3 projects_
- [Configuration](#configuration) _5 projects_
- [Debugging](#debugging) _1 projects_
- [Logging](#logging) _1 projects_
- [Authentication and Authorization](#authentication-and-authorization) _15 projects_
- [Task Queues](#task-queues) _5 projects_
- [Finite State Machine](#finite-state-machine) _5 projects_
- [RESTful API (Django Rest Framework)](#restful-api-django-rest-framework) _3 projects_
- [RESTful API (Django Ninja)](#restful-api-django-ninja) _6 projects_
- [Pydantic integration](#pydantic-integration) _3 projects_
- [GraphQL API](#graphql-api) _6 projects_
- [Feature Flipper](#feature-flipper) _1 projects_
- [Statistics](#statistics) _1 projects_
- [Testing](#testing) _5 projects_
- [CMS frameworks based on Django](#cms-frameworks-based-on-django) _3 projects_
- [E-Commerce frameworks based on Django](#e-commerce-frameworks-based-on-django) _4 projects_
- [Fields (encrypted)](#fields-encrypted) _6 projects_
- [Fields (phone numbers)](#fields-phone-numbers) _2 projects_
- [Fields (addresses)](#fields-addresses) _5 projects_
- [Fields (versioning)](#fields-versioning) _7 projects_
- [Messaging](#messaging) _5 projects_
- [Storage](#storage) _3 projects_
- [Event Sourcing](#event-sourcing) _5 projects_
- [Locking](#locking) _3 projects_
- [Example data](#example-data) _4 projects_
- [Fake data](#fake-data) _2 projects_
- [CSS Framework Integration (Django MVT application)](#css-framework-integration-django-mvt-application) _6 projects_
- [Data exploration](#data-exploration) _1 projects_
- [Multiple tenants](#multiple-tenants) _4 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(12 months no activity)_
- 💀&nbsp; Dead project _(60 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>

## Admin Interface

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to replace or improve the default Django admin interface._

<details><summary><b><a href="https://github.com/fabiocaccamo/django-admin-interface">django-admin-interface</a></b> (🥇31 ·  ⭐ 1.5K) - djangos default admin interface with superpowers - customizable themes, popup windows replaced by modals and many.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-admin-interface) (👨‍💻 33 · 🔀 140 · 📦 3.2K · 📋 180 - 10% open · ⏱️ 05.08.2023):

	```
	git clone https://github.com/fabiocaccamo/django-admin-interface
	```
- [PyPi](https://pypi.org/project/django-admin-interface) (📥 70K / month):
	```
	pip install django-admin-interface
	```
</details>
<details><summary><b><a href="https://github.com/farridav/django-jazzmin">django-jazzmin</a></b> (🥈30 ·  ⭐ 1.3K) - Jazzy theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/farridav/django-jazzmin) (👨‍💻 62 · 🔀 220 · 📦 5.7K · 📋 230 - 38% open · ⏱️ 02.02.2023):

	```
	git clone https://github.com/farridav/django-jazzmin
	```
- [PyPi](https://pypi.org/project/django-jazzmin) (📥 100K / month):
	```
	pip install django-jazzmin
	```
</details>
<details><summary><b><a href="https://github.com/sehmaschine/django-grappelli">django-grappelli</a></b> (🥈28 ·  ⭐ 3.5K) - A jazzy skin for the Django Admin-Interface (official repository). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sehmaschine/django-grappelli) (👨‍💻 83 · 🔀 630 · 📦 5.8K · 📋 700 - 0% open · ⏱️ 15.08.2023):

	```
	git clone https://github.com/sehmaschine/django-grappelli
	```
- [PyPi](https://pypi.org/project/django-grappelli) (📥 160K / month):
	```
	pip install django-grappelli
	```
</details>
<details><summary><b><a href="https://github.com/kmmbvnr/django-material">django-material</a></b> (🥈28 ·  ⭐ 2.5K) - Material Design for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/kmmbvnr/django-material) (👨‍💻 41 · 🔀 410 · 📦 1.7K · 📋 410 - 4% open · ⏱️ 12.04.2023):

	```
	git clone https://github.com/viewflow/django-material
	```
- [PyPi](https://pypi.org/project/django-material) (📥 13K / month):
	```
	pip install django-material
	```
</details>
<details><summary><b><a href="https://github.com/geex-arts/django-jet">django-jet</a></b> (🥉26 ·  ⭐ 3.5K · 💤) - Modern responsive template for the Django admin interface with improved functionality. We are proud to announce.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/geex-arts/django-jet) (👨‍💻 29 · 🔀 670 · 📦 3K · 📋 340 - 63% open · ⏱️ 21.05.2019):

	```
	git clone https://github.com/geex-arts/django-jet
	```
- [PyPi](https://pypi.org/project/django-jet) (📥 18K / month):
	```
	pip install django-jet
	```
</details>
<details><summary><b><a href="https://github.com/otto-torino/django-baton">django-baton</a></b> (🥉25 ·  ⭐ 760 · ➕) - A cool, modern and responsive django admin application based on bootstrap 5 - https://otto-torino.github.io/tag/baton/. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/otto-torino/django-baton) (👨‍💻 15 · 🔀 82 · 📦 300 · 📋 170 - 3% open · ⏱️ 11.08.2023):

	```
	git clone https://github.com/otto-torino/django-baton
	```
- [PyPi](https://pypi.org/project/django-baton) (📥 5.8K / month):
	```
	pip install django-baton
	```
</details>
<details><summary><b><a href="https://github.com/django-admin-tools/django-admin-tools">django-admin-tools</a></b> (🥉24 ·  ⭐ 770) - Extends the Django Admin to include a extensible dashboard and navigation menu. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-admin-tools/django-admin-tools) (👨‍💻 82 · 🔀 110 · 📦 1.4K · 📋 78 - 21% open · ⏱️ 10.08.2023):

	```
	git clone https://github.com/django-admin-tools/django-admin-tools
	```
- [PyPi](https://pypi.org/project/django-admin-tools) (📥 40K / month):
	```
	pip install django-admin-tools
	```
</details>
<details><summary><b><a href="https://github.com/byashimov/django-controlcenter">django-controlcenter</a></b> (🥉21 ·  ⭐ 950) - Set of widgets to build dashboards for Django projects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/byashimov/django-controlcenter) (👨‍💻 18 · 🔀 84 · 📦 80 · 📋 33 - 30% open · ⏱️ 06.08.2023):

	```
	git clone https://github.com/byashimov/django-controlcenter
	```
- [PyPi](https://pypi.org/project/django-controlcenter) (📥 3.3K / month):
	```
	pip install django-controlcenter
	```
</details>
<br>

## Admin Interface Actions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-import-export/django-import-export">django-import-export</a></b> (🥇36 ·  ⭐ 2.7K) - Django application and library for importing and exporting data with admin integration. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/django-import-export/django-import-export) (👨‍💻 200 · 🔀 710 · 📦 68K · 📋 920 - 9% open · ⏱️ 20.07.2023):

	```
	git clone https://github.com/django-import-export/django-import-export
	```
- [PyPi](https://pypi.org/project/django-import-export) (📥 870K / month):
	```
	pip install django-import-export
	```
</details>
<details><summary><b><a href="https://github.com/jrief/django-admin-sortable2">django-admin-sortable2</a></b> (🥈30 ·  ⭐ 640) - Generic drag-and-drop ordering for objects in the Django admin interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jrief/django-admin-sortable2) (👨‍💻 84 · 🔀 170 · 📦 2K · 📋 210 - 18% open · ⏱️ 01.08.2023):

	```
	git clone https://github.com/jrief/django-admin-sortable2
	```
- [PyPi](https://pypi.org/project/django-admin-sortable2) (📥 180K / month):
	```
	pip install django-admin-sortable2
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-admin-sortable">django-admin-sortable</a></b> (🥉20 ·  ⭐ 550 · 💤) - Generic drag-and-drop ordering for objects and tabular inlines in Django Admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-admin-sortable) (👨‍💻 80 · 🔀 130 · 📦 640 · 📋 140 - 6% open · ⏱️ 13.03.2022):

	```
	git clone https://github.com/jazzband/django-admin-sortable
	```
- [PyPi](https://pypi.org/project/django-admin-sortable) (📥 62K / month):
	```
	pip install django-admin-sortable
	```
</details>
<details><summary><b><a href="https://github.com/TrangPham/django-admin-confirm">django-admin-confirm</a></b> (🥉14 ·  ⭐ 110) - AdminConfirmMixin is a mixin for ModelAdmin that adds confirmations to changes, additions and actions. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TrangPham/django-admin-confirm) (👨‍💻 6 · 🔀 11 · 📦 25 · 📋 25 - 32% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/trangpham/django-admin-confirm
	```
- [PyPi](https://pypi.org/project/django-admin-confirm) (📥 17K / month):
	```
	pip install django-admin-confirm
	```
</details>
<br>

## Admin Interface Filters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/lukasvinclav/django-admin-numeric-filter">django-admin-numeric-filter</a></b> (🥇18 ·  ⭐ 70) - Numeric filters for Django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lukasvinclav/django-admin-numeric-filter) (👨‍💻 14 · 🔀 32 · 📦 160 · 📋 16 - 18% open · ⏱️ 16.02.2023):

	```
	git clone https://github.com/lukasvinclav/django-admin-numeric-filter
	```
- [PyPi](https://pypi.org/project/django-admin-numeric-filter) (📥 15K / month):
	```
	pip install django-admin-numeric-filter
	```
</details>
<br>

## Management Commands

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add or help working with management commands._

<details><summary><b><a href="https://github.com/django-extensions/django-extensions">django-extensions</a></b> (🥇37 ·  ⭐ 6.2K · 📉) - This is a repository for collecting global custom management extensions for the Django Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-extensions/django-extensions) (👨‍💻 570 · 🔀 1.1K · 📦 180K · 📋 870 - 17% open · ⏱️ 05.06.2023):

	```
	git clone https://github.com/django-extensions/django-extensions
	```
- [PyPi](https://pypi.org/project/django-extensions) (📥 2.8M / month):
	```
	pip install django-extensions
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-dbbackup">django-dbbackup</a></b> (🥉29 ·  ⭐ 780) - Management commands to help backup and restore your project database and media files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-dbbackup) (👨‍💻 64 · 🔀 180 · 📦 1.6K · 📋 270 - 23% open · ⏱️ 12.12.2022):

	```
	git clone https://github.com/jazzband/django-dbbackup
	```
- [PyPi](https://pypi.org/project/django-dbbackup) (📥 65K / month):
	```
	pip install django-dbbackup
	```
</details>
<details><summary><b><a href="https://github.com/GaretJax/django-click">django-click</a></b> (🥉19 ·  ⭐ 230 · 💤) - Write Django management command using the click CLI library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/GaretJax/django-click) (👨‍💻 11 · 🔀 16 · 📦 250 · 📋 17 - 52% open · ⏱️ 17.03.2022):

	```
	git clone https://github.com/GaretJax/django-click
	```
- [PyPi](https://pypi.org/project/django-click) (📥 34K / month):
	```
	pip install django-click
	```
</details>
<br>

## Configuration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/joke2k/django-environ">django-environ</a></b> (🥇35 ·  ⭐ 2.8K) - Django-environ allows you to utilize 12factor inspired environment variables to configure your Django application. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/django-environ) (👨‍💻 84 · 🔀 300 · 📥 15 · 📦 180K · 📋 230 - 25% open · ⏱️ 02.03.2023):

	```
	git clone https://github.com/joke2k/django-environ
	```
- [PyPi](https://pypi.org/project/django-environ) (📥 1.4M / month):
	```
	pip install django-environ
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-constance">django-constance</a></b> (🥈29 ·  ⭐ 1.6K) - Dynamic Django settings. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-constance) (👨‍💻 140 · 🔀 280 · 📦 1.8K · 📋 270 - 9% open · ⏱️ 29.07.2023):

	```
	git clone https://github.com/jazzband/django-constance
	```
- [PyPi](https://pypi.org/project/django-constance) (📥 200K / month):
	```
	pip install django-constance
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-split-settings">django-split-settings</a></b> (🥉27 ·  ⭐ 1K) - Organize Django settings into multiple files and directories. Easily override and modify settings. Use wildcards and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-split-settings) (👨‍💻 23 · 🔀 62 · 📦 2.1K · 📋 44 - 9% open · ⏱️ 14.08.2023):

	```
	git clone https://github.com/wemake-services/django-split-settings
	```
- [PyPi](https://pypi.org/project/django-split-settings) (📥 93K / month):
	```
	pip install django-split-settings
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-configurations">django-configurations</a></b> (🥉27 ·  ⭐ 1K) - A helper for organizing Django project settings by relying on well established programming patterns. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-configurations) (👨‍💻 64 · 🔀 130 · 📦 2.7K · 📋 190 - 24% open · ⏱️ 04.04.2023):

	```
	git clone https://github.com/jazzband/django-configurations
	```
- [PyPi](https://pypi.org/project/django-configurations) (📥 120K / month):
	```
	pip install django-configurations
	```
</details>
<details><summary><b><a href="https://github.com/fabiocaccamo/django-extra-settings">django-extra-settings</a></b> (🥉23 ·  ⭐ 370) - config and manage typed extra settings using just the django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-extra-settings) (👨‍💻 12 · 🔀 24 · 📦 52 · 📋 24 - 4% open · ⏱️ 18.07.2023):

	```
	git clone https://github.com/fabiocaccamo/django-extra-settings
	```
- [PyPi](https://pypi.org/project/django-extra-settings) (📥 7K / month):
	```
	pip install django-extra-settings
	```
</details>
<br>

## Debugging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/django-debug-toolbar">django-debug-toolbar</a></b> (🥇36 ·  ⭐ 7.6K · 📉) - A configurable set of panels that display various debug information about the current request/response. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-debug-toolbar) (👨‍💻 270 · 🔀 890 · 📥 210 · 📦 76K · 📋 860 - 8% open · ⏱️ 18.08.2023):

	```
	git clone https://github.com/jazzband/django-debug-toolbar
	```
- [PyPi](https://pypi.org/project/django-debug-toolbar) (📥 2.1M / month):
	```
	pip install django-debug-toolbar
	```
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which improve logging and debugging._

<details><summary><b><a href="https://github.com/snok/django-guid">django-guid</a></b> (🥇21 ·  ⭐ 360) - Inject an ID into every log message from a Django request. ASGI compatible, integrates with Sentry, and works with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snok/django-guid) (👨‍💻 8 · 🔀 19 · 📦 100 · 📋 24 - 16% open · ⏱️ 16.06.2023):

	```
	git clone https://github.com/snok/django-guid
	```
- [PyPi](https://pypi.org/project/django-guid) (📥 88K / month):
	```
	pip install django-guid
	```
</details>
<br>

## Authentication and Authorization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pennersr/django-allauth">django-allauth</a></b> (🥇34 ·  ⭐ 8.2K · 📈) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-allauth) (👨‍💻 650 · 🔀 2.7K · 📦 10 · 📋 2K - 7% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/pennersr/django-allauth
	```
- [PyPi](https://pypi.org/project/django-allauth) (📥 730K / month):
	```
	pip install django-allauth
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-two-factor-auth">django-two-factor-auth</a></b> (🥇32 ·  ⭐ 1.5K · ➕) - Complete Two-Factor Authentication for Django providing the easiest integration into most Django projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-two-factor-auth) (👨‍💻 90 · 🔀 390 · 📦 990 · 📋 340 - 23% open · ⏱️ 15.08.2023):

	```
	git clone https://github.com/jazzband/django-two-factor-auth
	```
- [PyPi](https://pypi.org/project/django-two-factor-auth) (📥 180K / month):
	```
	pip install django-two-factor-auth
	```
</details>
<details><summary><b><a href="https://github.com/python-social-auth/social-app-django">social-app-django</a></b> (🥈30 ·  ⭐ 1.8K) - Python Social Auth - Application - Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-social-auth/social-app-django) (👨‍💻 320 · 🔀 340 · 📦 34K · 📋 270 - 46% open · ⏱️ 15.08.2023):

	```
	git clone https://github.com/python-social-auth/social-app-django
	```
- [PyPi](https://pypi.org/project/social-app-django):
	```
	pip install social-app-django
	```
</details>
<details><summary><b><a href="https://github.com/django-guardian/django-guardian">django-guardian</a></b> (🥈29 ·  ⭐ 3.4K · 💤) - Per object permissions for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-guardian/django-guardian) (👨‍💻 160 · 🔀 530 · 📦 6.1K · 📋 450 - 28% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/django-guardian/django-guardian
	```
- [PyPi](https://pypi.org/project/django-guardian) (📥 460K / month):
	```
	pip install django-guardian
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-oauth-toolkit">django-oauth-toolkit</a></b> (🥈28 ·  ⭐ 2.9K) - OAuth2 goodies for the Djangonauts!. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-oauth-toolkit) (👨‍💻 230 · 🔀 710 · 📋 770 - 21% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/jazzband/django-oauth-toolkit
	```
- [PyPi](https://pypi.org/project/django-oauth-toolkit) (📥 460K / month):
	```
	pip install django-oauth-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/juanifioren/django-oidc-provider">django-oidc-provider</a></b> (🥈26 ·  ⭐ 370 · 📉) - OpenID Connect and OAuth2 provider implementation for Djangonauts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/juanifioren/django-oidc-provider) (👨‍💻 70 · 🔀 210 · 📦 260 · 📋 200 - 28% open · ⏱️ 16.05.2023):

	```
	git clone https://github.com/juanifioren/django-oidc-provider
	```
- [PyPi](https://pypi.org/project/django-oidc-provider) (📥 11K / month):
	```
	pip install django-oidc-provider
	```
</details>
<details><summary><b><a href="https://github.com/django-otp/django-otp">django-otp</a></b> (🥉25 ·  ⭐ 430 · ➕) - A pluggable framework for adding two-factor authentication to Django using one-time passwords. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/django-otp/django-otp) (👨‍💻 43 · 🔀 83 · 📦 2.2K · 📋 68 - 14% open · ⏱️ 07.07.2023):

	```
	git clone https://github.com/django-otp/django-otp
	```
- [PyPi](https://pypi.org/project/django-otp) (📥 490K / month):
	```
	pip install django-otp
	```
</details>
<details><summary><b><a href="https://github.com/django-cas-ng/django-cas-ng">django-cas-ng</a></b> (🥉25 ·  ⭐ 360) - Django CAS 1.0/2.0/3.0 client authentication library, support Django 2.0, 2.1, 2.2, 3.0 and Python 3.5+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-cas-ng/django-cas-ng) (👨‍💻 83 · 🔀 160 · 📥 540 · 📦 460 · ⏱️ 27.06.2023):

	```
	git clone https://github.com/django-cas-ng/django-cas-ng
	```
- [PyPi](https://pypi.org/project/django-cas-ng) (📥 16K / month):
	```
	pip install django-cas-ng
	```
</details>
<details><summary><b><a href="https://github.com/snok/django-auth-adfs">django-auth-adfs</a></b> (🥉25 ·  ⭐ 240) - A Django authentication backend for Microsoft ADFS and AzureAD. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/snok/django-auth-adfs) (👨‍💻 44 · 🔀 85 · 📦 100 · 📋 180 - 9% open · ⏱️ 15.07.2023):

	```
	git clone https://github.com/snok/django-auth-adfs
	```
- [PyPi](https://pypi.org/project/django-auth-adfs) (📥 33K / month):
	```
	pip install django-auth-adfs
	```
</details>
<details><summary><b><a href="https://github.com/bennylope/django-organizations">django-organizations</a></b> (🥉22 ·  ⭐ 1.2K) - Multi-user accounts for Django projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/bennylope/django-organizations) (👨‍💻 47 · 🔀 190 · 📋 150 - 10% open · ⏱️ 23.05.2023):

	```
	git clone https://github.com/bennylope/django-organizations
	```
- [PyPi](https://pypi.org/project/django-organizations) (📥 37K / month):
	```
	pip install django-organizations
	```
</details>
<details><summary><b><a href="https://github.com/caffeinehit/django-oauth2-provider">django-oauth2-provider</a></b> (🥉19 ·  ⭐ 340) - Provide OAuth2 access to your app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/caffeinehit/django-oauth2-provider) (👨‍💻 16 · 🔀 180 · 📦 20 · 📋 65 - 61% open · ⏱️ 03.02.2023):

	```
	git clone https://github.com/caffeinehit/django-oauth2-provider
	```
- [PyPi](https://pypi.org/project/django-oauth2-provider) (📥 6.2K / month):
	```
	pip install django-oauth2-provider
	```
</details>
<details><summary><b><a href="https://github.com/idlesign/django-oauthost">django-oauthost</a></b> (🥉6 ·  ⭐ 25 · 💤) - Reusable application for Django, introducing OAuth2 server functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/idlesign/django-oauthost) (👨‍💻 2 · 📦 2 · 📋 3 - 33% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/idlesign/django-oauthost
	```
- [PyPi](https://pypi.org/project/django-oauthost) (📥 120 / month):
	```
	pip install django-oauthost
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/dimagi/django-prbac">django-prbac</a></b> (🥉16 ·  ⭐ 120) -  <code>❗Unlicensed</code>
- <b><a href="https://github.com/jrd/django-oauth2-authcodeflow">django-oauth2-authcodeflow</a></b> (🥉11 ·  ⭐ 11) - Authenticate with any OpenId Connect/Oauth2 provider through authorization code flow. PKCE is also supported. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dropseed/django-oauth-login">django-oauth-login</a></b> (🥉11 ·  ⭐ 11) - A minimal app that adds OAuth login support to your Django project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Task Queues

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/celery/celery">celery</a></b> (🥇44 ·  ⭐ 22K) - Distributed Task Queue (development branch). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.3K · 🔀 4.3K · 📦 110K · 📋 4.9K - 11% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 7.4M / month):
	```
	pip install celery
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥈37 ·  ⭐ 9.1K) - Simple job queues for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 300 · 🔀 1.3K · 📦 14K · 📋 1.1K - 13% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 1M / month):
	```
	pip install rq
	```
</details>
<details><summary><b><a href="https://github.com/rq/django-rq">django-rq</a></b> (🥉31 ·  ⭐ 1.7K · 📉) - A simple app that provides django integration for RQ (Redis Queue). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rq/django-rq) (👨‍💻 120 · 🔀 260 · 📦 2.8K · 📋 330 - 24% open · ⏱️ 02.06.2023):

	```
	git clone https://github.com/rq/django-rq
	```
- [PyPi](https://pypi.org/project/django-rq) (📥 190K / month):
	```
	pip install django-rq
	```
</details>
<details><summary><b><a href="https://github.com/Koed00/django-q">django-q</a></b> (🥉29 ·  ⭐ 1.7K · 💤) - A multiprocessing distributed task queue for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Koed00/django-q) (👨‍💻 62 · 🔀 220 · 📦 1.4K · 📋 420 - 65% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/Koed00/django-q
	```
- [PyPi](https://pypi.org/project/django-q) (📥 64K / month):
	```
	pip install django-q
	```
</details>
<details><summary><b><a href="https://github.com/celery/django-celery-beat">django-celery-beat</a></b> (🥉25 ·  ⭐ 1.4K) - Celery Periodic Tasks backed by the Django ORM. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/django-celery-beat) (👨‍💻 110 · 🔀 380 · 📋 370 - 19% open · ⏱️ 09.08.2023):

	```
	git clone https://github.com/celery/django-celery-beat
	```
- [PyPi](https://pypi.org/project/django-celery-beat) (📥 1.1M / month):
	```
	pip install django-celery-beat
	```
</details>
<br>

## Finite State Machine

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement Finite State Machines (e.g. to implement workflows)._

<details><summary><b><a href="https://github.com/viewflow/django-fsm">django-fsm</a></b> (🥇29 ·  ⭐ 2.2K) - Django friendly finite state machine support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/viewflow/django-fsm) (👨‍💻 67 · 🔀 270 · 📦 1.5K · 📋 160 - 11% open · ⏱️ 19.01.2023):

	```
	git clone https://github.com/viewflow/django-fsm
	```
- [PyPi](https://pypi.org/project/django-fsm) (📥 290K / month):
	```
	pip install django-fsm
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-fsm-log">django-fsm-log</a></b> (🥈24 ·  ⭐ 220) - Automatic logging for Django FSM. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-fsm-log) (👨‍💻 26 · 🔀 68 · 📦 130 · 📋 45 - 24% open · ⏱️ 26.04.2023):

	```
	git clone https://github.com/jazzband/django-fsm-log
	```
- [PyPi](https://pypi.org/project/django-fsm-log) (📥 37K / month):
	```
	pip install django-fsm-log
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/viewflow">viewflow</a></b> (🥉22 ·  ⭐ 2.4K) - Reusable workflow library for Django. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/viewflow/viewflow) (👨‍💻 2 · 🔀 370 · 📦 280 · 📋 290 - 10% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/viewflow/viewflow
	```
- [PyPi](https://pypi.org/project/viewflow) (📥 47 / month):
	```
	pip install viewflow
	```
</details>
<details><summary><b><a href="https://github.com/gadventures/django-fsm-admin">django-fsm-admin</a></b> (🥉19 ·  ⭐ 200) - Mixin and template tags to integrate django-fsm transitions into the django admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gadventures/django-fsm-admin) (👨‍💻 32 · 🔀 82 · 📦 320 · 📋 38 - 47% open · ⏱️ 25.10.2022):

	```
	git clone https://github.com/gadventures/django-fsm-admin
	```
- [PyPi](https://pypi.org/project/django-fsm-admin) (📥 88K / month):
	```
	pip install django-fsm-admin
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/ming-tung/django-fsm-freeze">django-fsm-freeze</a></b> (🥉9 ·  ⭐ 4) - django-fsm data immutability support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## RESTful API (Django Rest Framework)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/encode/django-rest-framework">django-rest-framework</a></b> (🥇41 ·  ⭐ 26K) - Web APIs for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/encode/django-rest-framework) (👨‍💻 1.4K · 🔀 6.4K · 📦 550K · 📋 3.8K - 1% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/encode/django-rest-framework
	```
- [PyPi](https://pypi.org/project/django-rest-framework) (📥 100K / month):
	```
	pip install django-rest-framework
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/djangorestframework-simplejwt">djangorestframework-simplejwt</a></b> (🥉28 ·  ⭐ 3.5K) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/djangorestframework-simplejwt) (👨‍💻 100 · 🔀 580 · 📋 420 - 25% open · ⏱️ 10.08.2023):

	```
	git clone https://github.com/jazzband/djangorestframework-simplejwt
	```
- [PyPi](https://pypi.org/project/djangorestframework-simplejwt) (📥 1.4M / month):
	```
	pip install djangorestframework-simplejwt
	```
</details>
<details><summary><b><a href="https://github.com/anexia-it/django-rest-passwordreset">django-rest-passwordreset</a></b> (🥉26 ·  ⭐ 380) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anexia-it/django-rest-passwordreset) (👨‍💻 34 · 🔀 130 · 📦 2.7K · 📋 100 - 28% open · ⏱️ 10.07.2023):

	```
	git clone https://github.com/anexia-it/django-rest-passwordreset
	```
- [PyPi](https://pypi.org/project/django-rest-passwordreset) (📥 340K / month):
	```
	pip install django-rest-passwordreset
	```
</details>
<br>

## RESTful API (Django Ninja)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/vitalik/django-ninja">django-ninja</a></b> (🥇33 ·  ⭐ 4.8K) - Fast, Async-ready, Openapi, type hints based framework for building APIs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vitalik/django-ninja) (👨‍💻 95 · 🔀 280 · 📦 1.5K · 📋 540 - 31% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/vitalik/django-ninja
	```
- [PyPi](https://pypi.org/project/django-ninja) (📥 150K / month):
	```
	pip install django-ninja
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-jwt">django-ninja-jwt</a></b> (🥈20 ·  ⭐ 65) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-jwt) (👨‍💻 78 · 🔀 8 · 📦 81 · ⏱️ 09.08.2023):

	```
	git clone https://github.com/eadwinCode/django-ninja-jwt
	```
- [PyPi](https://pypi.org/project/django-ninja-jwt) (📥 10K / month):
	```
	pip install django-ninja-jwt
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-extra">django-ninja-extra</a></b> (🥈19 ·  ⭐ 170) - Django Ninja Extra - Class-Based Utility and more for Django Ninja(Fast Django REST framework). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-extra) (👨‍💻 9 · 🔀 17 · 📋 23 - 13% open · ⏱️ 09.08.2023):

	```
	git clone https://github.com/eadwinCode/django-ninja-extra
	```
- [PyPi](https://pypi.org/project/django-ninja-extra) (📥 17K / month):
	```
	pip install django-ninja-extra
	```
</details>
<details><summary><b><a href="https://github.com/mawassk/django-ninja-apikey">django-ninja-apikey</a></b> (🥉13 ·  ⭐ 23 · 💤) - Easy to use API key authentication for Django Ninja REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mawassk/django-ninja-apikey) (🔀 5 · 📦 4 · 📋 3 - 66% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/mawassk/django-ninja-apikey
	```
- [PyPi](https://pypi.org/project/django-ninja-apikey) (📥 1.1K / month):
	```
	pip install django-ninja-apikey
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/eadwinCode/django-ninja-passwordreset">django-ninja-passwordreset</a></b> (🥉11 ·  ⭐ 3) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mugartec/django-ninja-auth">django-ninja-auth</a></b> (🥉7 ·  ⭐ 19) -  <code><a href="https://tldrlegal.com/search?q=WTFPL">❗️WTFPL</a></code>
</details>
<br>

## Pydantic integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pydantic/pydantic">pydantic</a></b> (🥇45 ·  ⭐ 15K) - Data validation using Python type hints. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydantic/pydantic) (👨‍💻 400 · 🔀 1.3K · 📦 240K · 📋 3K - 11% open · ⏱️ 18.08.2023):

	```
	git clone https://github.com/pydantic/pydantic
	```
- [PyPi](https://pypi.org/project/pydantic) (📥 91M / month):
	```
	pip install pydantic
	```
</details>
<details><summary><b><a href="https://github.com/jordaneremieff/djantic">djantic</a></b> (🥉20 ·  ⭐ 370) - Pydantic model support for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jordaneremieff/djantic) (👨‍💻 4 · 🔀 28 · 📦 58 · 📋 38 - 28% open · ⏱️ 13.02.2023):

	```
	git clone https://github.com/jordaneremieff/djantic
	```
- [PyPi](https://pypi.org/project/djantic) (📥 17K / month):
	```
	pip install djantic
	```
</details>
<details><summary><b><a href="https://github.com/yezz123/pyngo">pyngo</a></b> (🥉15 ·  ⭐ 57) - Pydantic model support for Django & Django-Rest-Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/yezz123/pyngo) (👨‍💻 5 · 🔀 5 · 📦 8 · 📋 2 - 50% open · ⏱️ 03.08.2023):

	```
	git clone https://github.com/yezz123/pyngo
	```
- [PyPi](https://pypi.org/project/pyngo) (📥 6.9K / month):
	```
	pip install pyngo
	```
</details>
<br>

## GraphQL API

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement GraphQL API._

<details><summary><b><a href="https://github.com/graphql-python/graphene">graphene</a></b> (🥇37 ·  ⭐ 7.8K) - GraphQL framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene) (👨‍💻 200 · 🔀 790 · 📦 18K · 📋 970 - 10% open · ⏱️ 26.07.2023):

	```
	git clone https://github.com/graphql-python/graphene
	```
- [PyPi](https://pypi.org/project/graphene) (📥 1.8M / month):
	```
	pip install graphene
	```
</details>
<details><summary><b><a href="https://github.com/graphql-python/graphene-django">graphene-django</a></b> (🥈34 ·  ⭐ 4.1K) - Build powerful, efficient, and flexible GraphQL APIs with seamless Django integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene-django) (👨‍💻 210 · 🔀 710 · 📦 13K · 📋 790 - 16% open · ⏱️ 11.08.2023):

	```
	git clone https://github.com/graphql-python/graphene-django
	```
- [PyPi](https://pypi.org/project/graphene-django) (📥 430K / month):
	```
	pip install graphene-django
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry">strawberry</a></b> (🥈33 ·  ⭐ 3.4K) - A GraphQL library for Python that leverages type annotations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry) (👨‍💻 220 · 🔀 430 · 📥 370 · 📦 2.1K · 📋 800 - 38% open · ⏱️ 15.08.2023):

	```
	git clone https://github.com/strawberry-graphql/strawberry
	```
- [PyPi](https://pypi.org/project/strawberry) (📥 470 / month):
	```
	pip install strawberry
	```
</details>
<details><summary><b><a href="https://github.com/flavors/django-graphql-jwt">django-graphql-jwt</a></b> (🥉31 ·  ⭐ 790 · 📈) - JSON Web Token (JWT) authentication for Graphene Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/flavors/django-graphql-jwt) (👨‍💻 24 · 🔀 150 · 📦 4.7K · 📋 220 - 22% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/flavors/django-graphql-jwt
	```
- [PyPi](https://pypi.org/project/django-graphql-jwt) (📥 110K / month):
	```
	pip install django-graphql-jwt
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry-graphql-django">strawberry-graphql-django</a></b> (🥉28 ·  ⭐ 290) - Strawberry GraphQL Django extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry-graphql-django) (👨‍💻 50 · 🔀 70 · 📦 300 · 📋 180 - 28% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/strawberry-graphql/strawberry-graphql-django
	```
- [PyPi](https://pypi.org/project/strawberry-graphql-django) (📥 60K / month):
	```
	pip install strawberry-graphql-django
	```
</details>
<details><summary><b><a href="https://github.com/PedroBern/django-graphql-auth">django-graphql-auth</a></b> (🥉21 ·  ⭐ 320 · 💤) - Django registration and authentication with GraphQL. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PedroBern/django-graphql-auth) (👨‍💻 16 · 🔀 94 · 📦 620 · 📋 100 - 57% open · ⏱️ 17.06.2022):

	```
	git clone https://github.com/PedroBern/django-graphql-auth
	```
- [PyPi](https://pypi.org/project/django-graphql-auth) (📥 9.6K / month):
	```
	pip install django-graphql-auth
	```
</details>
<br>

## Feature Flipper

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-waffle/django-waffle">django-waffle</a></b> (🥇30 ·  ⭐ 1K) - A feature flipper for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-waffle/django-waffle) (👨‍💻 120 · 🔀 230 · 📦 1.2K · 📋 200 - 18% open · ⏱️ 26.07.2023):

	```
	git clone https://github.com/django-waffle/django-waffle
	```
- [PyPi](https://pypi.org/project/django-waffle) (📥 380K / month):
	```
	pip install django-waffle
	```
</details>
<br>

## Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add application layer statistic functionality._

<details><summary><b><a href="https://github.com/pennersr/django-trackstats">django-trackstats</a></b> (🥇16 ·  ⭐ 410) - Keep track of your statistics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-trackstats) (👨‍💻 9 · 🔀 36 · 📦 22 · 📋 11 - 27% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/pennersr/django-trackstats
	```
- [PyPi](https://pypi.org/project/django-trackstats) (📥 1.2K / month):
	```
	pip install django-trackstats
	```
</details>
<br>

## Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model_bakery</a></b> (🥇27 ·  ⭐ 700) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 48 · 🔀 80 · 📦 3.2K · 📋 120 - 19% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model_bakery) (📥 450K / month):
	```
	pip install model_bakery
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-test-migrations">django-test-migrations</a></b> (🥈26 ·  ⭐ 440) - Test django schema and data migrations, including migrations order and best practices. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-test-migrations) (👨‍💻 18 · 🔀 27 · 📦 600 · 📋 60 - 20% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/wemake-services/django-test-migrations
	```
- [PyPi](https://pypi.org/project/django-test-migrations) (📥 100K / month):
	```
	pip install django-test-migrations
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥉25 ·  ⭐ 3.2K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 130 · 🔀 360 · 📋 550 - 29% open · ⏱️ 16.08.2023):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 3M / month):
	```
	pip install factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-django">pytest-django</a></b> (🥉25 ·  ⭐ 1.2K) - A Django plugin for pytest. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-django) (👨‍💻 140 · 🔀 310 · 📋 510 - 28% open · ⏱️ 05.04.2023):

	```
	git clone https://github.com/pytest-dev/pytest-django
	```
- [PyPi](https://pypi.org/project/pytest-django) (📥 2.4M / month):
	```
	pip install pytest-django
	```
</details>
<details><summary><b><a href="https://github.com/revsys/django-test-plus">django-test-plus</a></b> (🥉19 ·  ⭐ 580) - Useful additions to Djangos default TestCase. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/revsys/django-test-plus) (👨‍💻 33 · 🔀 59 · 📋 56 - 17% open · ⏱️ 11.07.2023):

	```
	git clone https://github.com/revsys/django-test-plus
	```
- [PyPi](https://pypi.org/project/django-test-plus) (📥 57K / month):
	```
	pip install django-test-plus
	```
</details>
<br>

## CMS frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Content Management Systems which use Django under the hood._

<details><summary><b><a href="https://github.com/django-cms/django-cms">django-cms</a></b> (🥇39 ·  ⭐ 9.5K) - The easy-to-use and developer-friendly enterprise CMS powered by Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-cms/django-cms) (👨‍💻 630 · 🔀 2.9K · 📦 4.9K · 📋 3.4K - 2% open · ⏱️ 08.08.2023):

	```
	git clone https://github.com/django-cms/django-cms
	```
- [PyPi](https://pypi.org/project/django-cms) (📥 44K / month):
	```
	pip install django-cms
	```
</details>
<details><summary><b><a href="https://github.com/wagtail/wagtail">wagtail</a></b> (🥉37 ·  ⭐ 15K) - A Django content management system focused on flexibility and user experience. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wagtail/wagtail) (👨‍💻 830 · 🔀 3.2K · 📦 6 · 📋 4.5K - 18% open · ⏱️ 18.08.2023):

	```
	git clone https://github.com/wagtail/wagtail
	```
- [PyPi](https://pypi.org/project/wagtail) (📥 160K / month):
	```
	pip install wagtail
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/mezzanine">mezzanine</a></b> (🥉26 ·  ⭐ 4.6K) - CMS framework for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/mezzanine) (👨‍💻 330 · 🔀 1.6K · 📋 1.1K - 3% open · ⏱️ 02.11.2022):

	```
	git clone https://github.com/stephenmcd/mezzanine
	```
- [PyPi](https://pypi.org/project/mezzanine) (📥 2.8K / month):
	```
	pip install mezzanine
	```
</details>
<br>

## E-Commerce frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_E-Commerce frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/django-oscar/django-oscar">django-oscar</a></b> (🥇35 ·  ⭐ 5.8K · 📉) - Domain-driven e-commerce for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-oscar/django-oscar) (👨‍💻 350 · 🔀 2K · 📦 1K · 📋 1.5K - 5% open · ⏱️ 14.07.2023):

	```
	git clone https://github.com/django-oscar/django-oscar
	```
- [PyPi](https://pypi.org/project/django-oscar) (📥 14K / month):
	```
	pip install django-oscar
	```
</details>
<details><summary><b><a href="https://github.com/saleor/saleor">saleor</a></b> (🥈33 ·  ⭐ 19K) - Saleor Core: the high performance, composable, headless commerce API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/saleor/saleor) (👨‍💻 280 · 🔀 4.9K · 📥 15 · 📦 3 · 📋 3.8K - 14% open · ⏱️ 18.08.2023):

	```
	git clone https://github.com/saleor/saleor
	```
- [PyPi](https://pypi.org/project/saleor) (📥 31 / month):
	```
	pip install saleor
	```
</details>
<details><summary><b><a href="https://github.com/awesto/django-shop">django-shop</a></b> (🥉26 ·  ⭐ 3K · 💤) - A Django based shop system. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/awesto/django-shop) (👨‍💻 96 · 🔀 970 · 📦 220 · 📋 380 - 22% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/awesto/django-shop
	```
- [PyPi](https://pypi.org/project/django-shop) (📥 4.6K / month):
	```
	pip install django-shop
	```
</details>
<details><summary><b><a href="https://github.com/shuup/shuup">shuup</a></b> (🥉24 ·  ⭐ 2.1K · 💤) - E-Commerce Platform. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/shuup/shuup) (👨‍💻 67 · 🔀 1K · 📥 580 · 📦 130 · 📋 440 - 33% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/shuup/shuup
	```
- [PyPi](https://pypi.org/project/shuup) (📥 1.2K / month):
	```
	pip install shuup
	```
</details>
<br>

## Fields (encrypted)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/orcasgit/django-fernet-fields">django-fernet-fields</a></b> (🥇20 ·  ⭐ 180 · 💤) - Fernet symmetric encryption for Django model fields. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/orcasgit/django-fernet-fields) (👨‍💻 9 · 🔀 54 · 📦 630 · 📋 16 - 56% open · ⏱️ 10.05.2019):

	```
	git clone https://github.com/orcasgit/django-fernet-fields
	```
- [PyPi](https://pypi.org/project/django-fernet-fields) (📥 70K / month):
	```
	pip install django-fernet-fields
	```
</details>
<details><summary><b><a href="https://github.com/georgemarshall/django-cryptography">django-cryptography</a></b> (🥈17 ·  ⭐ 330) - Easily encrypt data in Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/georgemarshall/django-cryptography) (👨‍💻 4 · 🔀 54 · 📋 68 - 52% open · ⏱️ 19.04.2023):

	```
	git clone https://github.com/georgemarshall/django-cryptography
	```
- [PyPi](https://pypi.org/project/django-cryptography) (📥 100K / month):
	```
	pip install django-cryptography
	```
</details>
<details><summary><b><a href="https://github.com/luojilab/django-mirage-field">django-mirage-field</a></b> (🥈17 ·  ⭐ 86 · 💤) - Django model field encrypt/decrypt your data, keep secret in database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/luojilab/django-mirage-field) (👨‍💻 9 · 🔀 13 · 📦 66 · 📋 13 - 7% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/luojilab/django-mirage-field
	```
- [PyPi](https://pypi.org/project/django-mirage-field) (📥 13K / month):
	```
	pip install django-mirage-field
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/foundertherapy/django-cryptographic-fields">django-cryptographic-fields</a></b> (🥉14 ·  ⭐ 27 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/lansharkconsulting/django/django-encrypted-model-fields">django-encrypted-model-fields</a></b> (🥉11 ·  ⭐ 32 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code>❗Unlicensed</code>
- <b><a href="https://gitlab.com/guywillett/django-searchable-encrypted-fields">django-searchable-encrypted-fields</a></b> (🥉6 ·  ⭐ 9 · 💤) -  <code>❗Unlicensed</code>
</details>
<br>

## Fields (phone numbers)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/stefanfoulis/django-phonenumber-field">django-phonenumber-field</a></b> (🥇34 ·  ⭐ 1.4K) - A django model and form field for normalised phone numbers using python-phonenumbers. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-phonenumber-field) (👨‍💻 110 · 🔀 290 · 📥 13 · 📦 22K · 📋 210 - 3% open · ⏱️ 09.08.2023):

	```
	git clone https://github.com/stefanfoulis/django-phonenumber-field
	```
- [PyPi](https://pypi.org/project/django-phonenumber-field) (📥 750K / month):
	```
	pip install django-phonenumber-field
	```
</details>
<details><summary><b><a href="https://github.com/VeryApt/django-phone-field">django-phone-field</a></b> (🥉18 ·  ⭐ 49 · 💤) - Lightweight model and form field for phone numbers in Django. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/VeryApt/django-phone-field) (👨‍💻 4 · 🔀 14 · 📦 2.8K · 📋 14 - 21% open · ⏱️ 10.06.2020):

	```
	git clone https://github.com/VeryApt/django-phone-field
	```
- [PyPi](https://pypi.org/project/django-phone-field) (📥 15K / month):
	```
	pip install django-phone-field
	```
</details>
<br>

## Fields (addresses)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/furious-luke/django-address">django-address</a></b> (🥇24 ·  ⭐ 410 · 💤) - A Django address model and field. Addresses may be specified by address components or by performing an automatic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/furious-luke/django-address) (👨‍💻 22 · 🔀 150 · 📦 370 · 📋 120 - 32% open · ⏱️ 05.05.2022):

	```
	git clone https://github.com/furious-luke/django-address
	```
- [PyPi](https://pypi.org/project/django-address) (📥 15K / month):
	```
	pip install django-address
	```
</details>
<details><summary><b><a href="https://github.com/madisona/django-google-maps">django-google-maps</a></b> (🥈20 ·  ⭐ 270 · 💤) - Using the Google Maps API with django model admin. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madisona/django-google-maps) (👨‍💻 19 · 🔀 92 · 📦 580 · 📋 46 - 26% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/madisona/django-google-maps
	```
- [PyPi](https://pypi.org/project/django-google-maps) (📥 4.9K / month):
	```
	pip install django-google-maps
	```
</details>
<details><summary><b><a href="https://github.com/openwisp/django-loci">django-loci</a></b> (🥈20 ·  ⭐ 170) - Reusable Django app for storing geographic and indoor coordinates. Maintained by the OpenWISP Project. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/openwisp/django-loci) (👨‍💻 28 · 🔀 38 · 📦 10 · 📋 40 - 5% open · ⏱️ 06.07.2023):

	```
	git clone https://github.com/openwisp/django-loci
	```
- [PyPi](https://pypi.org/project/django-loci) (📥 490 / month):
	```
	pip install django-loci
	```
</details>
<details><summary><b><a href="https://github.com/simon-the-shark/django-mapbox-location-field">django-mapbox-location-field</a></b> (🥉19 ·  ⭐ 63 · 💤) - Simple in use location model and form field with MapInput widget for picking some location. Uses mapbox gl js,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/simon-the-shark/django-mapbox-location-field) (👨‍💻 8 · 🔀 22 · 📦 290 · 📋 24 - 8% open · ⏱️ 07.04.2022):

	```
	git clone https://github.com/Simon-the-Shark/django-mapbox-location-field
	```
- [PyPi](https://pypi.org/project/django-mapbox-location-field) (📥 760 / month):
	```
	pip install django-mapbox-location-field
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/agusmakmun/django-address-model">django-address-model</a></b> (🥉8 ·  ⭐ 13 · 💤) - django abstract model that provide the complete address, eg: no, na/rt, ca/rw, village/desa, sub district/kecamatan,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Fields (versioning)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/django-simple-history">django-simple-history</a></b> (🥇37 ·  ⭐ 1.9K) - Store model history and view/revert changes from admin site. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-simple-history) (👨‍💻 180 · 🔀 420 · 📦 4.3K · 📋 520 - 23% open · ⏱️ 18.08.2023):

	```
	git clone https://github.com/jazzband/django-simple-history
	```
- [PyPi](https://pypi.org/project/django-simple-history) (📥 1.1M / month):
	```
	pip install django-simple-history
	```
</details>
<details><summary><b><a href="https://github.com/etianen/django-reversion">django-reversion</a></b> (🥈32 ·  ⭐ 2.9K) - django-reversion is an extension to the Django web framework that provides version control for model instances. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/etianen/django-reversion) (👨‍💻 190 · 🔀 450 · 📦 7.1K · 📋 640 - 2% open · ⏱️ 21.05.2023):

	```
	git clone https://github.com/etianen/django-reversion
	```
- [PyPi](https://pypi.org/project/django-reversion) (📥 290K / month):
	```
	pip install django-reversion
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-auditlog">django-auditlog</a></b> (🥈28 ·  ⭐ 850) - A Django app that keeps a log of changes made to an object. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-auditlog) (👨‍💻 68 · 🔀 330 · 📥 300 · 📦 720 · 📋 240 - 20% open · ⏱️ 13.08.2023):

	```
	git clone https://github.com/jazzband/django-auditlog
	```
- [PyPi](https://pypi.org/project/django-auditlog) (📥 210K / month):
	```
	pip install django-auditlog
	```
</details>
<details><summary><b><a href="https://github.com/soynatan/django-easy-audit">django-easy-audit</a></b> (🥉23 ·  ⭐ 580) - Yet another Django audit log app, hopefully the simplest one. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/soynatan/django-easy-audit) (👨‍💻 45 · 🔀 150 · 📦 190 · 📋 130 - 46% open · ⏱️ 13.06.2023):

	```
	git clone https://github.com/soynatan/django-easy-audit
	```
- [PyPi](https://pypi.org/project/django-easy-audit) (📥 40K / month):
	```
	pip install django-easy-audit
	```
</details>
<details><summary><b><a href="https://github.com/romgar/django-dirtyfields">django-dirtyfields</a></b> (🥉19 ·  ⭐ 580) - Tracking dirty fields on a Django model. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/romgar/django-dirtyfields) (👨‍💻 41 · 🔀 97 · 📋 69 - 15% open · ⏱️ 01.07.2023):

	```
	git clone https://github.com/romgar/django-dirtyfields
	```
- [PyPi](https://pypi.org/project/django-dirtyfields) (📥 170K / month):
	```
	pip install django-dirtyfields
	```
</details>
<details><summary><b><a href="https://github.com/craigds/django-fieldsignals">django-fieldsignals</a></b> (🥉16 ·  ⭐ 110) - Django signals for changed fields. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/craigds/django-fieldsignals) (👨‍💻 5 · 🔀 11 · 📦 190 · 📋 17 - 17% open · ⏱️ 08.10.2022):

	```
	git clone https://github.com/craigds/django-fieldsignals
	```
- [PyPi](https://pypi.org/project/django-fieldsignals) (📥 11K / month):
	```
	pip install django-fieldsignals
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/vvangelovski/django-audit-log">django-audit-log</a></b> (🥉17 ·  ⭐ 230 · 💀) - Audit log for your Django models. <code>❗Unlicensed</code>
</details>
<br>

## Messaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/lamby/django-slack">django-slack</a></b> (🥇21 ·  ⭐ 230) - Slack integration for Django, using the templating engine to generate messages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lamby/django-slack) (👨‍💻 28 · 🔀 55 · 📦 350 · 📋 63 - 14% open · ⏱️ 02.03.2023):

	```
	git clone https://github.com/lamby/django-slack
	```
- [PyPi](https://pypi.org/project/django-slack) (📥 59K / month):
	```
	pip install django-slack
	```
</details>
<details><summary><b><a href="https://github.com/stefanfoulis/django-sendsms">django-sendsms</a></b> (🥈17 ·  ⭐ 250 · 💤) - A simple API to send SMS messages. It is modeled after the django email api. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-sendsms) (👨‍💻 19 · 🔀 94 · 📦 340 · 📋 24 - 20% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/stefanfoulis/django-sendsms
	```
- [PyPi](https://pypi.org/project/django-sendsms) (📥 3.8K / month):
	```
	pip install django-sendsms
	```
</details>
<details><summary><b><a href="https://github.com/roaldnefs/django-sms">django-sms</a></b> (🥉15 ·  ⭐ 43) - A Django app for sending SMS with interchangeable backends. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/roaldnefs/django-sms) (👨‍💻 3 · 🔀 12 · 📦 170 · 📋 14 - 42% open · ⏱️ 25.12.2022):

	```
	git clone https://github.com/roaldnefs/django-sms
	```
- [PyPi](https://pypi.org/project/django-sms) (📥 6.3K / month):
	```
	pip install django-sms
	```
</details>
<details><summary><b><a href="https://github.com/Ninjaclasher/django-discord-integration">django-discord-integration</a></b> (🥉7 ·  ⭐ 20) - Discord integration for Django, supporting error reporting via webhooks. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Ninjaclasher/django-discord-integration) (👨‍💻 2 · 🔀 1 · 📦 4 · ⏱️ 08.04.2023):

	```
	git clone https://github.com/Ninjaclasher/django-discord-integration
	```
- [PyPi](https://pypi.org/project/django-discord-integration) (📥 170 / month):
	```
	pip install django-discord-integration
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/AdvocatesInc/django-channels-discord">django-channels-discord</a></b> (🥉5 ·  ⭐ 12 · 💤) - An interface server connecting Djangos Channels and Discord. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Storage

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jschneier/django-storages">django-storages</a></b> (🥇25 ·  ⭐ 2.5K) - https://django-storages.readthedocs.io/. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jschneier/django-storages) (👨‍💻 250 · 🔀 770 · 📋 640 - 26% open · ⏱️ 02.08.2023):

	```
	git clone https://github.com/jschneier/django-storages
	```
- [PyPi](https://pypi.org/project/django-storages) (📥 2.3M / month):
	```
	pip install django-storages
	```
</details>
<details><summary><b><a href="https://github.com/py-pa/django-minio-storage">django-minio-storage</a></b> (🥉23 ·  ⭐ 130) - A django storage driver for minio. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py-pa/django-minio-storage) (👨‍💻 16 · 🔀 46 · 📦 200 · 📋 79 - 11% open · ⏱️ 13.07.2023):

	```
	git clone https://github.com/py-pa/django-minio-storage
	```
- [PyPi](https://pypi.org/project/django-minio-storage) (📥 22K / month):
	```
	pip install django-minio-storage
	```
</details>
<details><summary><b><a href="https://github.com/maddevsio/django_minio">django-minio</a></b> (🥉7 ·  ⭐ 63 · 💤) - Django app to use Minio Server as file storage. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/maddevsio/django_minio) (👨‍💻 4 · 🔀 15 · 📋 5 - 20% open · ⏱️ 02.04.2019):

	```
	git clone https://github.com/maddevsio/django_minio
	```
- [PyPi](https://pypi.org/project/django-minio) (📥 130 / month):
	```
	pip install django-minio
	```
</details>
<br>

## Event Sourcing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing">eventsourcing</a></b> (🥇24 ·  ⭐ 1.3K) - A library for event sourcing in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing) (👨‍💻 23 · 🔀 130 · 📦 140 · 📋 81 - 2% open · ⏱️ 19.05.2023):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing
	```
- [PyPi](https://pypi.org/project/eventsourcing) (📥 11K / month):
	```
	pip install eventsourcing
	```
</details>
<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing-django">eventsourcing-django</a></b> (🥈11 ·  ⭐ 32) - Python package for eventsourcing with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing-django) (👨‍💻 5 · 🔀 7 · 📦 5 · 📋 3 - 66% open · ⏱️ 16.03.2023):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing-django
	```
- [PyPi](https://pypi.org/project/eventsourcing-django) (📥 1.5K / month):
	```
	pip install eventsourcing-django
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/pyeventsourcing/eventsourcing-eventstoredb">eventsourcing-eventstoredb</a></b> (🥉6 ·  ⭐ 11) - Python package for eventsourcing with EventStoreDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-dynamodb">eventsourcing-dynamodb</a></b> (🥉4 ·  ⭐ 3) - Python package for eventsourcing with DynamoDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-axonserver">eventsourcing-axonserver</a></b> (🥉4 ·  ⭐ 1) - Python package for eventsourcing with Axon Server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Locking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/saxix/django-concurrency">django-concurrency</a></b> (🥇19 ·  ⭐ 420) - Optimistic lock implementation for Django. Prevents users from doing concurrent editing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/saxix/django-concurrency) (👨‍💻 24 · 🔀 47 · 📋 70 - 12% open · ⏱️ 04.08.2022):

	```
	git clone https://github.com/saxix/django-concurrency
	```
- [PyPi](https://pypi.org/project/django-concurrency) (📥 38K / month):
	```
	pip install django-concurrency
	```
</details>
<details><summary><b><a href="https://github.com/gavinwahl/django-optimistic-lock">django-optimistic-lock</a></b> (🥉14 ·  ⭐ 120 · 💤) - Offline optimistic locking for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/gavinwahl/django-optimistic-lock) (👨‍💻 4 · 🔀 21 · 📦 12 · 📋 5 - 20% open · ⏱️ 02.01.2019):

	```
	git clone https://github.com/gavinwahl/django-optimistic-lock
	```
- [PyPi](https://pypi.org/project/django-optimistic-lock) (📥 4.8K / month):
	```
	pip install django-optimistic-lock
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/debrouwere/django-locking">django-locking</a></b> (🥉8 ·  ⭐ 140 · 💀) - Prevents users from doing concurrent editing in Django. Works out of the box in the admin interface, or you can.. <code>❗Unlicensed</code>
</details>
<br>

## Example data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Brobin/django-seed">django-seed</a></b> (🥇25 ·  ⭐ 640 · 💤) - Seed your Django database with fake data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Brobin/django-seed) (👨‍💻 23 · 🔀 74 · 📦 3.9K · 📋 56 - 25% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/brobin/django-seed
	```
- [PyPi](https://pypi.org/project/django-seed) (📥 30K / month):
	```
	pip install django-seed
	```
</details>
<details><summary><b><a href="https://github.com/davedash/django-fixture-magic">django-fixture-magic</a></b> (🥉19 ·  ⭐ 380 · 💤) - Utilities to extract and manipulate Django Fixtures. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/davedash/django-fixture-magic) (👨‍💻 35 · 🔀 89 · 📦 140 · 📋 35 - 34% open · ⏱️ 12.03.2021):

	```
	git clone https://github.com/davedash/django-fixture-magic
	```
- [PyPi](https://pypi.org/project/django-fixture-magic) (📥 25K / month):
	```
	pip install django-fixture-magic
	```
</details>
<details><summary><b><a href="https://github.com/klen/mixer">mixer</a></b> (🥉17 ·  ⭐ 910 · 💤) - Mixer -- Is a fixtures replacement. Supported Django, Flask, SqlAlchemy and custom python objects. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/klen/mixer) (👨‍💻 43 · 🔀 91 · 📋 85 - 42% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/klen/mixer
	```
- [PyPi](https://pypi.org/project/mixer) (📥 97K / month):
	```
	pip install mixer
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/gregmuellegger/django-autofixture">django-autofixture</a></b> (🥈21 ·  ⭐ 460 · 💀) - Can create auto-generated test data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Fake data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model-bakery</a></b> (🥇27 ·  ⭐ 700) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 48 · 🔀 80 · 📦 3.2K · 📋 120 - 19% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model-bakery/) (📥 450K / month):
	```
	pip install model-bakery/
	```
</details>
<details><summary><b><a href="https://github.com/paulocheque/django-dynamic-fixture">django-dynamic-fixture</a></b> (🥉22 ·  ⭐ 380 · 📈) - A complete library to create dynamic model instances for testing purposes. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/paulocheque/django-dynamic-fixture) (👨‍💻 36 · 🔀 60 · 📦 1.1K · 📋 67 - 7% open · ⏱️ 18.08.2023):

	```
	git clone https://github.com/paulocheque/django-dynamic-fixture
	```
- [PyPi](https://pypi.org/project/django-dynamic-fixture) (📥 59K / month):
	```
	pip install django-dynamic-fixture
	```
</details>
<br>

## CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/zostera/django-bootstrap4">django-bootstrap4</a></b> (🥇33 ·  ⭐ 1K) - Bootstrap 4 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap4) (👨‍💻 140 · 🔀 210 · 📦 130K · 📋 160 - 11% open · ⏱️ 28.06.2023):

	```
	git clone https://github.com/zostera/django-bootstrap4
	```
- [PyPi](https://pypi.org/project/django-bootstrap4) (📥 170K / month):
	```
	pip install django-bootstrap4
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap3">django-bootstrap3</a></b> (🥈31 ·  ⭐ 2.3K) - Bootstrap 3 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap3) (👨‍💻 99 · 🔀 680 · 📦 18K · 📋 300 - 1% open · ⏱️ 28.06.2023):

	```
	git clone https://github.com/zostera/django-bootstrap3
	```
- [PyPi](https://pypi.org/project/django-bootstrap3) (📥 84K / month):
	```
	pip install django-bootstrap3
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap5">django-bootstrap5</a></b> (🥈26 ·  ⭐ 280) - Bootstrap 5 for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap5) (👨‍💻 140 · 🔀 52 · 📦 4K · 📋 82 - 45% open · ⏱️ 29.06.2023):

	```
	git clone https://github.com/zostera/django-bootstrap5
	```
- [PyPi](https://pypi.org/project/django-bootstrap5) (📥 48K / month):
	```
	pip install django-bootstrap5
	```
</details>
<details><summary><b><a href="https://github.com/timonweb/django-tailwind">django-tailwind</a></b> (🥉24 ·  ⭐ 1.1K) - Django + Tailwind CSS =. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/django-tailwind) (👨‍💻 18 · 🔀 82 · 📦 2.3K · 📋 140 - 5% open · ⏱️ 22.06.2023):

	```
	git clone https://github.com/timonweb/django-tailwind
	```
- [PyPi](https://pypi.org/project/django-tailwind) (📥 39K / month):
	```
	pip install django-tailwind
	```
</details>
<details><summary><b><a href="https://github.com/zelenij/django-bootstrap-v5">django-bootstrap-v5</a></b> (🥉21 ·  ⭐ 92 · 💤) - Bootstrap 5 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zelenij/django-bootstrap-v5) (👨‍💻 140 · 🔀 43 · 📦 5.3K · 📋 21 - 33% open · ⏱️ 18.07.2022):

	```
	git clone https://github.com/zelenij/django-bootstrap-v5
	```
- [PyPi](https://pypi.org/project/django-bootstrap-v5) (📥 29K / month):
	```
	pip install django-bootstrap-v5
	```
</details>
<details><summary><b><a href="https://github.com/timonweb/django-bulma">django-bulma</a></b> (🥉18 ·  ⭐ 330 · 💤) - Bulma theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/django-bulma) (👨‍💻 14 · 🔀 52 · 📦 460 · 📋 41 - 9% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/timonweb/django-bulma
	```
- [PyPi](https://pypi.org/project/django-bulma) (📥 1.9K / month):
	```
	pip install django-bulma
	```
</details>
<br>

## Data exploration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tolomea/django-data-browser">django-data-browser</a></b> (🥇20 ·  ⭐ 240) - Django app for user friendly querying of Django models. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tolomea/django-data-browser) (👨‍💻 9 · 🔀 18 · 📦 10 · 📋 33 - 12% open · ⏱️ 20.07.2023):

	```
	git clone https://github.com/tolomea/django-data-browser
	```
- [PyPi](https://pypi.org/project/django-data-browser) (📥 2.7K / month):
	```
	pip install django-data-browser
	```
</details>
<br>

## Multiple tenants

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-tenants/django-tenants">django-tenants</a></b> (🥇31 ·  ⭐ 1.2K) - Django tenants using PostgreSQL Schemas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-tenants/django-tenants) (👨‍💻 100 · 🔀 290 · 📦 580 · 📋 610 - 31% open · ⏱️ 14.08.2023):

	```
	git clone https://github.com/django-tenants/django-tenants
	```
- [PyPi](https://pypi.org/project/django-tenants) (📥 71K / month):
	```
	pip install django-tenants
	```
</details>
<details><summary><b><a href="https://github.com/bernardopires/django-tenant-schemas">django-tenant-schemas</a></b> (🥈27 ·  ⭐ 1.4K) - Tenant support for Django using PostgreSQL schemas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bernardopires/django-tenant-schemas) (👨‍💻 75 · 🔀 390 · 📦 390 · 📋 470 - 30% open · ⏱️ 02.07.2023):

	```
	git clone https://github.com/bernardopires/django-tenant-schemas
	```
- [PyPi](https://pypi.org/project/django-tenant-schemas) (📥 15K / month):
	```
	pip install django-tenant-schemas
	```
</details>
<details><summary><b><a href="https://github.com/citusdata/django-multitenant">django-multitenant</a></b> (🥉25 ·  ⭐ 620) - Python/Django support for distributed multi-tenant databases like Postgres+Citus. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/citusdata/django-multitenant) (👨‍💻 23 · 🔀 95 · 📦 51 · 📋 81 - 32% open · ⏱️ 11.07.2023):

	```
	git clone https://github.com/citusdata/django-multitenant
	```
- [PyPi](https://pypi.org/project/django-multitenant) (📥 19K / month):
	```
	pip install django-multitenant
	```
</details>
<details><summary><b><a href="https://github.com/raphaelm/django-scopes">django-scopes</a></b> (🥉15 ·  ⭐ 200) - Safely separate multiple tenants in a Django database. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/raphaelm/django-scopes) (👨‍💻 6 · 🔀 15 · 📦 65 · 📋 16 - 62% open · ⏱️ 12.06.2023):

	```
	git clone https://github.com/raphaelm/django-scopes
	```
- [PyPi](https://pypi.org/project/django-scopes) (📥 3.6K / month):
	```
	pip install django-scopes
	```
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/fkromer/best-of-django/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/fkromer/best-of-django/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/fkromer/best-of-django/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/fkromer/best-of-django/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/fkromer/best-of-django/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
