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
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-230-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/fkromer/best-of-django/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/fkromer/best-of-django?color=green&label=updated"></a>
</p>

This curated list contains 230 awesome open-source projects with a total of 500K stars grouped into 59 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/fkromer/best-of-django/issues/new/choose), submit a [pull request](https://github.com/fkromer/best-of-django/pulls), or directly edit the [projects.yaml](https://github.com/fkromer/best-of-django/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Admin Interface](#admin-interface) _8 projects_
- [Admin Interface Actions](#admin-interface-actions) _4 projects_
- [Admin Interface Filters](#admin-interface-filters) _1 projects_
- [Management Commands](#management-commands) _5 projects_
- [Caching](#caching) _2 projects_
- [Configuration](#configuration) _6 projects_
- [Dependency Injection](#dependency-injection) _3 projects_
- [Debugging](#debugging) _1 projects_
- [Development](#development) _2 projects_
- [Logging](#logging) _5 projects_
- [Application Monitoring (Platforms)](#application-monitoring-platforms) _2 projects_
- [Authentication and Authorization](#authentication-and-authorization) _17 projects_
- [Authorization](#authorization) _1 projects_
- [Task Queues](#task-queues) _5 projects_
- [Finite State Machine](#finite-state-machine) _7 projects_
- [RESTful API (Django Rest Framework)](#restful-api-django-rest-framework) _5 projects_
- [RESTful API (Django Ninja)](#restful-api-django-ninja) _6 projects_
- [Pydantic integration](#pydantic-integration) _4 projects_
- [Pandas integration](#pandas-integration) _1 projects_
- [GraphQL API](#graphql-api) _8 projects_
- [Feature Flipper](#feature-flipper) _1 projects_
- [Statistics](#statistics) _1 projects_
- [Testing](#testing) _5 projects_
- [Monitoring frameworks based on Django](#monitoring-frameworks-based-on-django) _0 projects_
- [CMS frameworks based on Django](#cms-frameworks-based-on-django) _3 projects_
- [E-Commerce frameworks based on Django](#e-commerce-frameworks-based-on-django) _4 projects_
- [Analytics frameworks based on Django](#analytics-frameworks-based-on-django) _1 projects_
- [Project management frameworks based on Django](#project-management-frameworks-based-on-django) _2 projects_
- [Monitoring frameworks based on Django](#monitoring-frameworks-based-on-django) _0 projects_
- [Photo management frameworks based on Django](#photo-management-frameworks-based-on-django) _1 projects_
- [Recipe management frameworks based on Django](#recipe-management-frameworks-based-on-django) _1 projects_
- [Document management frameworks based on Django](#document-management-frameworks-based-on-django) _1 projects_
- [Education frameworks based on Django](#education-frameworks-based-on-django) _1 projects_
- [Inventory management system based on Django](#inventory-management-system-based-on-django) _1 projects_
- [Crawler management system based on Django](#crawler-management-system-based-on-django) _0 projects_
- [Network automation system based on Django](#network-automation-system-based-on-django) _1 projects_
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
- [Bootstrap CSS Framework Integration (Django MVT application)](#bootstrap-css-framework-integration-django-mvt-application) _4 projects_
- [Bulma CSS Framework Integration (Django MVT application)](#bulma-css-framework-integration-django-mvt-application) _1 projects_
- [TailwindCSS CSS Framework Integration (Django MVT application)](#tailwindcss-css-framework-integration-django-mvt-application) _3 projects_
- [Data exploration](#data-exploration) _1 projects_
- [Multiple tenants](#multiple-tenants) _4 projects_
- [Value-as-a-Service frameworks based on Django](#value-as-a-service-frameworks-based-on-django) _1 projects_
- [Payment and Subscription (Stripe, etc.)](#payment-and-subscription-stripe-etc) _19 projects_
- [Emails](#emails) _5 projects_
- [Templates](#templates) _4 projects_
- [Reusable app templates](#reusable-app-templates) _11 projects_
- [Project templates](#project-templates) _16 projects_
- [Static file serving](#static-file-serving) _1 projects_
- [Custom user](#custom-user) _5 projects_

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

<details><summary><b><a href="https://github.com/fabiocaccamo/django-admin-interface">django-admin-interface</a></b> (🥇33 ·  ⭐ 1.8K) - djangos default admin interface with superpowers - customizable themes, popup windows replaced by modals and many.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-admin-interface) (👨‍💻 38 · 🔀 170 · 📦 4.4K · 📋 200 - 7% open · ⏱️ 01.07.2024):

	```
	git clone https://github.com/fabiocaccamo/django-admin-interface
	```
- [PyPi](https://pypi.org/project/django-admin-interface) (📥 160K / month):
	```
	pip install django-admin-interface
	```
</details>
<details><summary><b><a href="https://github.com/farridav/django-jazzmin">django-jazzmin</a></b> (🥈31 ·  ⭐ 1.6K · 📉) - Jazzy theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/farridav/django-jazzmin) (👨‍💻 67 · 🔀 270 · 📦 12K · 📋 270 - 40% open · ⏱️ 11.08.2024):

	```
	git clone https://github.com/farridav/django-jazzmin
	```
- [PyPi](https://pypi.org/project/django-jazzmin) (📥 260K / month):
	```
	pip install django-jazzmin
	```
</details>
<details><summary><b><a href="https://github.com/sehmaschine/django-grappelli">django-grappelli</a></b> (🥈28 ·  ⭐ 3.7K) - A jazzy skin for the Django Admin-Interface (official repository). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/sehmaschine/django-grappelli) (👨‍💻 90 · 🔀 640 · 📦 6.3K · 📋 720 - 0% open · ⏱️ 22.08.2024):

	```
	git clone https://github.com/sehmaschine/django-grappelli
	```
- [PyPi](https://pypi.org/project/django-grappelli) (📥 200K / month):
	```
	pip install django-grappelli
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/django-material">django-material</a></b> (🥈28 ·  ⭐ 2.5K) - Material Design for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/viewflow/django-material) (👨‍💻 41 · 🔀 420 · 📦 1.8K · 📋 410 - 4% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/viewflow/django-material
	```
- [PyPi](https://pypi.org/project/django-material) (📥 13K / month):
	```
	pip install django-material
	```
</details>
<details><summary><b><a href="https://github.com/otto-torino/django-baton">django-baton</a></b> (🥉26 ·  ⭐ 870) - A cool, modern and responsive django admin application based on bootstrap 5 that brings AI to the Django admin -.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/otto-torino/django-baton) (👨‍💻 15 · 🔀 95 · 📦 410 · 📋 180 - 1% open · ⏱️ 19.07.2024):

	```
	git clone https://github.com/otto-torino/django-baton
	```
- [PyPi](https://pypi.org/project/django-baton) (📥 9.4K / month):
	```
	pip install django-baton
	```
</details>
<details><summary><b><a href="https://github.com/django-admin-tools/django-admin-tools">django-admin-tools</a></b> (🥉23 ·  ⭐ 860 · 💤) - Extends the Django Admin to include a extensible dashboard and navigation menu. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-admin-tools/django-admin-tools) (👨‍💻 82 · 🔀 110 · 📦 1.5K · 📋 80 - 23% open · ⏱️ 10.08.2023):

	```
	git clone https://github.com/django-admin-tools/django-admin-tools
	```
- [PyPi](https://pypi.org/project/django-admin-tools) (📥 54K / month):
	```
	pip install django-admin-tools
	```
</details>
<details><summary><b><a href="https://github.com/byashimov/django-controlcenter">django-controlcenter</a></b> (🥉20 ·  ⭐ 980 · 💤) - Set of widgets to build dashboards for Django projects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/byashimov/django-controlcenter) (👨‍💻 18 · 🔀 85 · 📦 86 · 📋 34 - 29% open · ⏱️ 06.08.2023):

	```
	git clone https://github.com/byashimov/django-controlcenter
	```
- [PyPi](https://pypi.org/project/django-controlcenter) (📥 9.8K / month):
	```
	pip install django-controlcenter
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/geex-arts/django-jet">django-jet</a></b> (🥉26 ·  ⭐ 3.6K · 💀) - Modern responsive template for the Django admin interface with improved functionality. We are proud to announce.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
</details>
<br>

## Admin Interface Actions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-import-export/django-import-export">django-import-export</a></b> (🥇39 ·  ⭐ 3K) - Django application and library for importing and exporting data with admin integration. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/django-import-export/django-import-export) (👨‍💻 220 · 🔀 750 · 📦 100K · 📋 1.1K - 1% open · ⏱️ 23.08.2024):

	```
	git clone https://github.com/django-import-export/django-import-export
	```
- [PyPi](https://pypi.org/project/django-import-export) (📥 1.4M / month):
	```
	pip install django-import-export
	```
</details>
<details><summary><b><a href="https://github.com/jrief/django-admin-sortable2">django-admin-sortable2</a></b> (🥈28 ·  ⭐ 730) - Generic drag-and-drop ordering for objects in the Django admin interface. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jrief/django-admin-sortable2) (👨‍💻 85 · 🔀 170 · 📦 2.5K · 📋 220 - 19% open · ⏱️ 15.08.2024):

	```
	git clone https://github.com/jrief/django-admin-sortable2
	```
- [PyPi](https://pypi.org/project/django-admin-sortable2) (📥 240K / month):
	```
	pip install django-admin-sortable2
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-admin-sortable">django-admin-sortable</a></b> (🥉19 ·  ⭐ 570 · 💤) - Generic drag-and-drop ordering for objects and tabular inlines in Django Admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-admin-sortable) (👨‍💻 80 · 🔀 130 · 📦 700 · 📋 140 - 7% open · ⏱️ 13.03.2022):

	```
	git clone https://github.com/jazzband/django-admin-sortable
	```
- [PyPi](https://pypi.org/project/django-admin-sortable) (📥 32K / month):
	```
	pip install django-admin-sortable
	```
</details>
<details><summary><b><a href="https://github.com/TrangPham/django-admin-confirm">django-admin-confirm</a></b> (🥉16 ·  ⭐ 130) - AdminConfirmMixin is a mixin for ModelAdmin that adds confirmations to changes, additions and actions. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TrangPham/django-admin-confirm) (👨‍💻 6 · 🔀 15 · 📦 86 · 📋 31 - 41% open · ⏱️ 27.01.2024):

	```
	git clone https://github.com/trangpham/django-admin-confirm
	```
- [PyPi](https://pypi.org/project/django-admin-confirm) (📥 27K / month):
	```
	pip install django-admin-confirm
	```
</details>
<br>

## Admin Interface Filters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/lukasvinclav/django-admin-numeric-filter">django-admin-numeric-filter</a></b> (🥇19 ·  ⭐ 79 · 💤) - Numeric filters for Django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lukasvinclav/django-admin-numeric-filter) (👨‍💻 14 · 🔀 32 · 📦 190 · 📋 18 - 22% open · ⏱️ 16.02.2023):

	```
	git clone https://github.com/lukasvinclav/django-admin-numeric-filter
	```
- [PyPi](https://pypi.org/project/django-admin-numeric-filter) (📥 20K / month):
	```
	pip install django-admin-numeric-filter
	```
</details>
<br>

## Management Commands

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add or help working with management commands._

<details><summary><b><a href="https://github.com/django-extensions/django-extensions">django-extensions</a></b> (🥇38 ·  ⭐ 6.5K) - This is a repository for collecting global custom management extensions for the Django Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-extensions/django-extensions) (👨‍💻 580 · 🔀 1.1K · 📦 230K · 📋 890 - 19% open · ⏱️ 27.04.2024):

	```
	git clone https://github.com/django-extensions/django-extensions
	```
- [PyPi](https://pypi.org/project/django-extensions) (📥 4.5M / month):
	```
	pip install django-extensions
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-dbbackup">django-dbbackup</a></b> (🥈31 ·  ⭐ 960) - Management commands to help backup and restore your project database and media files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-dbbackup) (👨‍💻 75 · 🔀 200 · 📦 2K · 📋 280 - 22% open · ⏱️ 23.08.2024):

	```
	git clone https://github.com/jazzband/django-dbbackup
	```
- [PyPi](https://pypi.org/project/django-dbbackup) (📥 130K / month):
	```
	pip install django-dbbackup
	```
</details>
<details><summary><b><a href="https://github.com/GaretJax/django-click">django-click</a></b> (🥉22 ·  ⭐ 250) - Write Django management command using the click CLI library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/GaretJax/django-click) (👨‍💻 13 · 🔀 19 · 📦 320 · 📋 18 - 44% open · ⏱️ 01.08.2024):

	```
	git clone https://github.com/GaretJax/django-click
	```
- [PyPi](https://pypi.org/project/django-click) (📥 57K / month):
	```
	pip install django-click
	```
</details>
<details><summary><b><a href="https://github.com/bckohan/django-typer">django-typer</a></b> (🥉19 ·  ⭐ 66) - Use Typer (type hints) to define the interface for your Django management commands. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bckohan/django-typer) (👨‍💻 4 · 🔀 2 · 📦 32 · 📋 71 - 19% open · ⏱️ 26.08.2024):

	```
	git clone https://github.com/bckohan/django-typer
	```
- [PyPi](https://pypi.org/project/django-typer) (📥 8.2K / month):
	```
	pip install django-typer
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/django-rich">django-rich</a></b> (🥉18 ·  ⭐ 120) - Extensions for using Rich with Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-rich) (👨‍💻 6 · 🔀 10 · 📦 140 · 📋 12 - 25% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/adamchainz/django-rich
	```
- [PyPi](https://pypi.org/project/django-rich) (📥 54K / month):
	```
	pip install django-rich
	```
</details>
<br>

## Caching

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Suor/django-cacheops">django-cacheops</a></b> (🥇29 ·  ⭐ 2.1K) - A slick ORM cache with automatic granular event-driven invalidation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Suor/django-cacheops) (👨‍💻 67 · 🔀 220 · 📦 1.3K · 📋 340 - 5% open · ⏱️ 26.06.2024):

	```
	git clone https://github.com/Suor/django-cacheops
	```
- [PyPi](https://pypi.org/project/django-cacheops) (📥 170K / month):
	```
	pip install django-cacheops
	```
</details>
<details><summary><b><a href="https://github.com/noripyt/django-cachalot">django-cachalot</a></b> (🥉27 ·  ⭐ 1.2K) - No effort, no worry, maximum performance. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/noripyt/django-cachalot) (👨‍💻 37 · 🔀 140 · 📦 820 · 📋 170 - 19% open · ⏱️ 12.08.2024):

	```
	git clone https://github.com/noripyt/django-cachalot
	```
- [PyPi](https://pypi.org/project/django-cachalot) (📥 98K / month):
	```
	pip install django-cachalot
	```
</details>
<br>

## Configuration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/joke2k/django-environ">django-environ</a></b> (🥇33 ·  ⭐ 3K) - Django-environ allows you to utilize 12factor inspired environment variables to configure your Django application. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/joke2k/django-environ) (👨‍💻 93 · 🔀 310 · 📥 100 · 📦 230K · 📋 250 - 27% open · ⏱️ 01.09.2023):

	```
	git clone https://github.com/joke2k/django-environ
	```
- [PyPi](https://pypi.org/project/django-environ) (📥 2.8M / month):
	```
	pip install django-environ
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/dj-database-url">dj-database-url</a></b> (🥇33 ·  ⭐ 1.5K · ➕) - Use Database URLs in your Django Application. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/dj-database-url) (👨‍💻 72 · 🔀 200 · 📦 280K · 📋 95 - 4% open · ⏱️ 27.08.2024):

	```
	git clone https://github.com/jazzband/dj-database-url
	```
- [PyPi](https://pypi.org/project/dj-database-url) (📥 2.2M / month):
	```
	pip install dj-database-url
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-constance">django-constance</a></b> (🥈32 ·  ⭐ 1.7K · 📈) - Dynamic Django settings. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-constance) (👨‍💻 150 · 🔀 290 · 📦 2.1K · 📋 290 - 6% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/jazzband/django-constance
	```
- [PyPi](https://pypi.org/project/django-constance) (📥 310K / month):
	```
	pip install django-constance
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-split-settings">django-split-settings</a></b> (🥉29 ·  ⭐ 1.1K) - Organize Django settings into multiple files and directories. Easily override and modify settings. Use wildcards and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-split-settings) (👨‍💻 25 · 🔀 66 · 📦 3K · 📋 47 - 8% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/wemake-services/django-split-settings
	```
- [PyPi](https://pypi.org/project/django-split-settings) (📥 180K / month):
	```
	pip install django-split-settings
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-configurations">django-configurations</a></b> (🥉28 ·  ⭐ 1.1K) - A helper for organizing Django project settings by relying on well established programming patterns. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-configurations) (👨‍💻 66 · 🔀 140 · 📦 3.2K · 📋 200 - 24% open · ⏱️ 30.11.2023):

	```
	git clone https://github.com/jazzband/django-configurations
	```
- [PyPi](https://pypi.org/project/django-configurations) (📥 590K / month):
	```
	pip install django-configurations
	```
</details>
<details><summary><b><a href="https://github.com/fabiocaccamo/django-extra-settings">django-extra-settings</a></b> (🥉22 ·  ⭐ 510) - config and manage typed extra settings using just the django admin. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fabiocaccamo/django-extra-settings) (👨‍💻 12 · 🔀 30 · 📦 91 · 📋 34 - 11% open · ⏱️ 01.07.2024):

	```
	git clone https://github.com/fabiocaccamo/django-extra-settings
	```
- [PyPi](https://pypi.org/project/django-extra-settings) (📥 12K / month):
	```
	pip install django-extra-settings
	```
</details>
<br>

## Dependency Injection

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/python-injector/injector">injector</a></b> (🥇26 ·  ⭐ 1.3K · ➕) - Python dependency injection framework, inspired by Guice. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-injector/injector) (👨‍💻 31 · 🔀 79 · 📦 2.3K · 📋 140 - 30% open · ⏱️ 07.07.2024):

	```
	git clone https://github.com/python-injector/injector
	```
- [PyPi](https://pypi.org/project/injector) (📥 2.2M / month):
	```
	pip install injector
	```
</details>
<details><summary><b><a href="https://github.com/maldoinc/wireup">wireup</a></b> (🥉17 ·  ⭐ 87 · ➕) - Performant, concise, and easy-to-use dependency injection container for Python 3.8+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maldoinc/wireup) (👨‍💻 2 · 🔀 1 · 📦 4 · 📋 24 - 41% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/maldoinc/wireup
	```
- [PyPi](https://pypi.org/project/wireup) (📥 1.4K / month):
	```
	pip install wireup
	```
</details>
<details><summary><b><a href="https://github.com/blubber/django_injector">django_injector</a></b> (🥉11 ·  ⭐ 47 · ➕) - Dependency injection in Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/blubber/django_injector) (👨‍💻 7 · 🔀 7 · ⏱️ 09.04.2024):

	```
	git clone https://github.com/blubber/django_injector
	```
- [PyPi](https://pypi.org/project/django_injector) (📥 3.2K / month):
	```
	pip install django_injector
	```
</details>
<br>

## Debugging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/django-debug-toolbar">django-debug-toolbar</a></b> (🥇39 ·  ⭐ 8K) - A configurable set of panels that display various debug information about the current request/response. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-debug-toolbar) (👨‍💻 300 · 🔀 930 · 📥 220 · 📦 93K · 📋 910 - 6% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/jazzband/django-debug-toolbar
	```
- [PyPi](https://pypi.org/project/django-debug-toolbar) (📥 3.1M / month):
	```
	pip install django-debug-toolbar
	```
</details>
<br>

## Development

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/gauge-sh/tach">tach</a></b> (🥇26 ·  ⭐ 970 · ➕) - A Python tool to enforce dependencies, using modular architecture Open source Installable via pip Able to be adopted.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gauge-sh/tach) (👨‍💻 16 · 🔀 35 · 📦 14 · 📋 50 - 8% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/gauge-sh/tach
	```
- [PyPi](https://pypi.org/project/tach) (📥 48K / month):
	```
	pip install tach
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/django-browser-reload">django-browser-reload</a></b> (🥉25 ·  ⭐ 510) - Automatically reload your browser in development. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-browser-reload) (👨‍💻 6 · 🔀 26 · 📦 4.4K · 📋 38 - 31% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/adamchainz/django-browser-reload
	```
- [PyPi](https://pypi.org/project/django-browser-reload) (📥 130K / month):
	```
	pip install django-browser-reload
	```
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which improve logging and debugging._

<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥇37 ·  ⭐ 19K · ➕) - Python logging made (stupidly) simple. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 53 · 🔀 680 · 📦 94K · 📋 1K - 18% open · ⏱️ 20.07.2024):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 36M / month):
	```
	pip install loguru
	```
</details>
<details><summary><b><a href="https://github.com/hynek/structlog">structlog</a></b> (🥈35 ·  ⭐ 3.4K · ➕) - Simple, powerful, and fast logging for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/hynek/structlog) (👨‍💻 120 · 🔀 210 · 📦 13K · 📋 330 - 8% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/hynek/structlog
	```
- [PyPi](https://pypi.org/project/structlog) (📥 24M / month):
	```
	pip install structlog
	```
</details>
<details><summary><b><a href="https://github.com/jrobichaud/django-structlog">django-structlog</a></b> (🥉26 ·  ⭐ 420 · ➕) - Structured Logging for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jrobichaud/django-structlog) (👨‍💻 21 · 🔀 33 · 📦 620 · ⏱️ 02.09.2024):

	```
	git clone https://github.com/jrobichaud/django-structlog
	```
- [PyPi](https://pypi.org/project/django-structlog) (📥 420K / month):
	```
	pip install django-structlog
	```
</details>
<details><summary><b><a href="https://github.com/snok/django-guid">django-guid</a></b> (🥉23 ·  ⭐ 440) - Inject an ID into every log message from a Django request. ASGI compatible, integrates with Sentry, and works with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snok/django-guid) (👨‍💻 10 · 🔀 26 · 📦 160 · 📋 29 - 20% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/snok/django-guid
	```
- [PyPi](https://pypi.org/project/django-guid) (📥 82K / month):
	```
	pip install django-guid
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/tarsil/django-loguru">django-loguru</a></b> (🥉8 ·  ⭐ 10 · 💤) - A middleware to log the requests and responses using loguru. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Application Monitoring (Platforms)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/getsentry/sentry">sentry</a></b> (🥇39 ·  ⭐ 38K) - Developer-first error tracking and performance monitoring. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/getsentry/sentry) (👨‍💻 870 · 🔀 4.1K · 📥 45K · 📦 450 · 📋 13K - 20% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/getsentry/sentry
	```
- [PyPi](https://pypi.org/project/sentry) (📥 4.9K / month):
	```
	pip install sentry
	```
</details>
<details><summary><b><a href="https://github.com/pydantic/logfire">logfire</a></b> (🥉26 ·  ⭐ 1.9K · 🐣) - Uncomplicated Observability for Python and beyond!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydantic/logfire) (👨‍💻 29 · 🔀 54 · 📦 150 · 📋 140 - 36% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/pydantic/logfire
	```
- [PyPi](https://pypi.org/project/logfire) (📥 57K / month):
	```
	pip install logfire
	```
</details>
<br>

## Authentication and Authorization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pennersr/django-allauth">django-allauth</a></b> (🥇40 ·  ⭐ 9.4K) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-allauth) (👨‍💻 730 · 🔀 2.9K · 📦 230K · 📋 2.4K - 2% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/pennersr/django-allauth
	```
- [PyPi](https://pypi.org/project/django-allauth) (📥 950K / month):
	```
	pip install django-allauth
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-oauth-toolkit">django-oauth-toolkit</a></b> (🥇34 ·  ⭐ 3.1K · 📈) - OAuth2 goodies for the Djangonauts!. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-oauth-toolkit) (👨‍💻 260 · 🔀 750 · 📦 10K · 📋 850 - 20% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/jazzband/django-oauth-toolkit
	```
- [PyPi](https://pypi.org/project/django-oauth-toolkit) (📥 1.1M / month):
	```
	pip install django-oauth-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/python-social-auth/social-app-django">social-app-django</a></b> (🥈31 ·  ⭐ 2K) - Python Social Auth - Application - Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-social-auth/social-app-django) (👨‍💻 330 · 🔀 360 · 📦 45K · 📋 300 - 44% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/python-social-auth/social-app-django
	```
- [PyPi](https://pypi.org/project/social-app-django):
	```
	pip install social-app-django
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-two-factor-auth">django-two-factor-auth</a></b> (🥈31 ·  ⭐ 1.7K) - Complete Two-Factor Authentication for Django providing the easiest integration into most Django projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-two-factor-auth) (👨‍💻 100 · 🔀 420 · 📦 1.6K · 📋 370 - 22% open · ⏱️ 12.08.2024):

	```
	git clone https://github.com/jazzband/django-two-factor-auth
	```
- [PyPi](https://pypi.org/project/django-two-factor-auth) (📥 370K / month):
	```
	pip install django-two-factor-auth
	```
</details>
<details><summary><b><a href="https://github.com/django-guardian/django-guardian">django-guardian</a></b> (🥈27 ·  ⭐ 3.6K) - Per object permissions for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-guardian/django-guardian) (👨‍💻 160 · 🔀 550 · 📦 6.8K · 📋 460 - 27% open · ⏱️ 17.07.2024):

	```
	git clone https://github.com/django-guardian/django-guardian
	```
- [PyPi](https://pypi.org/project/django-guardian) (📥 350K / month):
	```
	pip install django-guardian
	```
</details>
<details><summary><b><a href="https://github.com/jsocol/django-ratelimit">django-ratelimit</a></b> (🥈26 ·  ⭐ 1.1K) - Cache-based rate-limiting for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jsocol/django-ratelimit) (👨‍💻 51 · 🔀 180 · 📦 2.8K · 📋 150 - 15% open · ⏱️ 05.12.2023):

	```
	git clone https://github.com/jsocol/django-ratelimit
	```
- [PyPi](https://pypi.org/project/django-ratelimit) (📥 770K / month):
	```
	pip install django-ratelimit
	```
</details>
<details><summary><b><a href="https://github.com/django-cas-ng/django-cas-ng">django-cas-ng</a></b> (🥈26 ·  ⭐ 380) - Django CAS 1.0/2.0/3.0 client authentication library, supporting Django 4.2+ and Python 3.8+. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-cas-ng/django-cas-ng) (👨‍💻 86 · 🔀 160 · 📥 640 · 📦 550 · 📋 160 - 2% open · ⏱️ 30.08.2024):

	```
	git clone https://github.com/django-cas-ng/django-cas-ng
	```
- [PyPi](https://pypi.org/project/django-cas-ng) (📥 41K / month):
	```
	pip install django-cas-ng
	```
</details>
<details><summary><b><a href="https://github.com/bennylope/django-organizations">django-organizations</a></b> (🥉25 ·  ⭐ 1.3K · 📉) - Multi-user accounts for Django projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/bennylope/django-organizations) (👨‍💻 50 · 🔀 200 · 📦 290 · 📋 150 - 8% open · ⏱️ 11.06.2024):

	```
	git clone https://github.com/bennylope/django-organizations
	```
- [PyPi](https://pypi.org/project/django-organizations) (📥 40K / month):
	```
	pip install django-organizations
	```
</details>
<details><summary><b><a href="https://github.com/django-otp/django-otp">django-otp</a></b> (🥉25 ·  ⭐ 530) - A pluggable framework for adding two-factor authentication to Django using one-time passwords. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/django-otp/django-otp) (👨‍💻 47 · 🔀 99 · 📦 3.2K · 📋 81 - 13% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/django-otp/django-otp
	```
- [PyPi](https://pypi.org/project/django-otp) (📥 900K / month):
	```
	pip install django-otp
	```
</details>
<details><summary><b><a href="https://github.com/snok/django-auth-adfs">django-auth-adfs</a></b> (🥉25 ·  ⭐ 270) - A Django authentication backend for Microsoft ADFS and AzureAD. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/snok/django-auth-adfs) (👨‍💻 47 · 🔀 93 · 📦 130 · 📋 200 - 14% open · ⏱️ 18.12.2023):

	```
	git clone https://github.com/snok/django-auth-adfs
	```
- [PyPi](https://pypi.org/project/django-auth-adfs) (📥 71K / month):
	```
	pip install django-auth-adfs
	```
</details>
<details><summary><b><a href="https://github.com/juanifioren/django-oidc-provider">django-oidc-provider</a></b> (🥉24 ·  ⭐ 420) - OpenID Connect and OAuth2 provider implementation for Djangonauts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/juanifioren/django-oidc-provider) (👨‍💻 74 · 🔀 220 · 📦 350 · 📋 200 - 27% open · ⏱️ 15.12.2023):

	```
	git clone https://github.com/juanifioren/django-oidc-provider
	```
- [PyPi](https://pypi.org/project/django-oidc-provider) (📥 16K / month):
	```
	pip install django-oidc-provider
	```
</details>
<details><summary><b><a href="https://github.com/valohai/django-allauth-2fa">django-allauth-2fa</a></b> (🥉23 ·  ⭐ 210) - Two-factor authentication for Django Allauth. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/valohai/django-allauth-2fa) (👨‍💻 32 · 🔀 49 · 📥 22 · 📦 210 · 📋 72 - 16% open · ⏱️ 19.04.2024):

	```
	git clone https://github.com/valohai/django-allauth-2fa
	```
- [PyPi](https://pypi.org/project/django-allauth-2fa) (📥 61K / month):
	```
	pip install django-allauth-2fa
	```
</details>
<details><summary><b><a href="https://github.com/caffeinehit/django-oauth2-provider">django-oauth2-provider</a></b> (🥉18 ·  ⭐ 340 · 💤) - Provide OAuth2 access to your app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/caffeinehit/django-oauth2-provider) (👨‍💻 16 · 🔀 180 · 📋 65 - 61% open · ⏱️ 03.02.2023):

	```
	git clone https://github.com/caffeinehit/django-oauth2-provider
	```
- [PyPi](https://pypi.org/project/django-oauth2-provider) (📥 7.4K / month):
	```
	pip install django-oauth2-provider
	```
</details>
<details><summary><b><a href="https://github.com/idlesign/django-oauthost">django-oauthost</a></b> (🥉7 ·  ⭐ 25 · 💤) - Reusable application for Django, introducing OAuth2 server functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/idlesign/django-oauthost) (👨‍💻 2 · 📦 3 · 📋 3 - 33% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/idlesign/django-oauthost
	```
- [PyPi](https://pypi.org/project/django-oauthost) (📥 85 / month):
	```
	pip install django-oauthost
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/dimagi/django-prbac">django-prbac</a></b> (🥉15 ·  ⭐ 140) -  <code>❗Unlicensed</code>
- <b><a href="https://github.com/jrd/django-oauth2-authcodeflow">django-oauth2-authcodeflow</a></b> (🥉14 ·  ⭐ 14) - Authenticate with any OpenId Connect/Oauth2 provider through authorization code flow. PKCE is also supported. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dropseed/django-oauth-login">django-oauth-login</a></b> (🥉11 ·  ⭐ 16 · 💤) - A minimal app that adds OAuth login support to your Django project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Authorization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/dfunckt/django-rules">django-rules</a></b> (🥇20 ·  ⭐ 1.8K · 📉) - Awesome Django authorization, without the database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dfunckt/django-rules) (👨‍💻 33 · 🔀 140 · 📋 110 - 23% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/dfunckt/django-rules
	```
- [PyPi](https://pypi.org/project/django-rules) (📥 86 / month):
	```
	pip install django-rules
	```
</details>
<br>

## Task Queues

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/celery/celery">celery</a></b> (🥇44 ·  ⭐ 24K) - Distributed Task Queue (development branch). <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.4K · 🔀 4.5K · 📦 140K · 📋 5.1K - 12% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 13M / month):
	```
	pip install celery
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥈38 ·  ⭐ 9.8K) - Simple job queues for Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 320 · 🔀 1.4K · 📦 17K · 📋 1.1K - 16% open · ⏱️ 25.08.2024):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 1.5M / month):
	```
	pip install rq
	```
</details>
<details><summary><b><a href="https://github.com/Koed00/django-q">django-q</a></b> (🥉31 ·  ⭐ 1.8K · 💤) - A multiprocessing distributed task queue for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Koed00/django-q) (👨‍💻 62 · 🔀 230 · 📦 1.7K · 📋 430 - 64% open · ⏱️ 26.06.2021):

	```
	git clone https://github.com/Koed00/django-q
	```
- [PyPi](https://pypi.org/project/django-q) (📥 100K / month):
	```
	pip install django-q
	```
</details>
<details><summary><b><a href="https://github.com/rq/django-rq">django-rq</a></b> (🥉30 ·  ⭐ 1.8K) - A simple app that provides django integration for RQ (Redis Queue). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rq/django-rq) (👨‍💻 130 · 🔀 280 · 📦 3.5K · 📋 350 - 26% open · ⏱️ 01.05.2024):

	```
	git clone https://github.com/rq/django-rq
	```
- [PyPi](https://pypi.org/project/django-rq) (📥 270K / month):
	```
	pip install django-rq
	```
</details>
<details><summary><b><a href="https://github.com/celery/django-celery-beat">django-celery-beat</a></b> (🥉26 ·  ⭐ 1.7K) - Celery Periodic Tasks backed by the Django ORM. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/celery/django-celery-beat) (👨‍💻 130 · 🔀 420 · 📋 410 - 22% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/celery/django-celery-beat
	```
- [PyPi](https://pypi.org/project/django-celery-beat) (📥 1.7M / month):
	```
	pip install django-celery-beat
	```
</details>
<br>

## Finite State Machine

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement Finite State Machines (e.g. to implement workflows)._

<details><summary><b><a href="https://github.com/pytransitions/transitions">transitions</a></b> (🥇34 ·  ⭐ 5.6K) - A lightweight, object-oriented finite state machine implementation in Python with many extensions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytransitions/transitions) (👨‍💻 78 · 🔀 510 · 📦 3.6K · 📋 460 - 1% open · ⏱️ 13.08.2024):

	```
	git clone https://github.com/pytransitions/transitions
	```
- [PyPi](https://pypi.org/project/transitions) (📥 790K / month):
	```
	pip install transitions
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/django-fsm">django-fsm</a></b> (🥈30 ·  ⭐ 2.3K) - Django friendly finite state machine support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/viewflow/django-fsm) (👨‍💻 70 · 🔀 290 · 📦 1.7K · 📋 160 - 0% open · ⏱️ 16.04.2024):

	```
	git clone https://github.com/viewflow/django-fsm
	```
- [PyPi](https://pypi.org/project/django-fsm) (📥 350K / month):
	```
	pip install django-fsm
	```
</details>
<details><summary><b><a href="https://github.com/viewflow/viewflow">viewflow</a></b> (🥈24 ·  ⭐ 2.7K) - Reusable workflow library for Django. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/viewflow/viewflow) (👨‍💻 2 · 🔀 400 · 📦 310 · 📋 350 - 5% open · ⏱️ 23.08.2024):

	```
	git clone https://github.com/viewflow/viewflow
	```
- [PyPi](https://pypi.org/project/viewflow) (📥 140 / month):
	```
	pip install viewflow
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-fsm-log">django-fsm-log</a></b> (🥉23 ·  ⭐ 240) - Automatic logging for Django FSM. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-fsm-log) (👨‍💻 27 · 🔀 75 · 📦 140 · 📋 47 - 23% open · ⏱️ 01.08.2024):

	```
	git clone https://github.com/jazzband/django-fsm-log
	```
- [PyPi](https://pypi.org/project/django-fsm-log) (📥 47K / month):
	```
	pip install django-fsm-log
	```
</details>
<details><summary><b><a href="https://github.com/gadventures/django-fsm-admin">django-fsm-admin</a></b> (🥉18 ·  ⭐ 200 · 💤) - Mixin and template tags to integrate django-fsm transitions into the django admin. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/gadventures/django-fsm-admin) (👨‍💻 32 · 🔀 94 · 📦 360 · 📋 39 - 48% open · ⏱️ 25.10.2022):

	```
	git clone https://github.com/gadventures/django-fsm-admin
	```
- [PyPi](https://pypi.org/project/django-fsm-admin) (📥 18K / month):
	```
	pip install django-fsm-admin
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/27medkamal/djangorestframework-fsm">djangorestframework-fsm</a></b> (🥉10 ·  ⭐ 18 · 💤) - Automatically hook your Django-FSM transitions up to Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ming-tung/django-fsm-freeze">django-fsm-freeze</a></b> (🥉8 ·  ⭐ 4) - django-fsm data immutability support. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## RESTful API (Django Rest Framework)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/encode/django-rest-framework">django-rest-framework</a></b> (🥇42 ·  ⭐ 28K) - Web APIs for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/encode/django-rest-framework) (👨‍💻 1.4K · 🔀 6.7K · 📦 710K · 📋 3.9K - 1% open · ⏱️ 27.08.2024):

	```
	git clone https://github.com/encode/django-rest-framework
	```
- [PyPi](https://pypi.org/project/django-rest-framework) (📥 110K / month):
	```
	pip install django-rest-framework
	```
</details>
<details><summary><b><a href="https://github.com/anexia-it/django-rest-passwordreset">django-rest-passwordreset</a></b> (🥈27 ·  ⭐ 420) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anexia-it/django-rest-passwordreset) (👨‍💻 38 · 🔀 140 · 📦 3.8K · 📋 100 - 27% open · ⏱️ 29.07.2024):

	```
	git clone https://github.com/anexia-it/django-rest-passwordreset
	```
- [PyPi](https://pypi.org/project/django-rest-passwordreset) (📥 180K / month):
	```
	pip install django-rest-passwordreset
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/djangorestframework-simplejwt">djangorestframework-simplejwt</a></b> (🥉26 ·  ⭐ 4K) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/djangorestframework-simplejwt) (👨‍💻 120 · 🔀 620 · 📋 470 - 27% open · ⏱️ 30.05.2024):

	```
	git clone https://github.com/jazzband/djangorestframework-simplejwt
	```
- [PyPi](https://pypi.org/project/djangorestframework-simplejwt) (📥 2.8M / month):
	```
	pip install djangorestframework-simplejwt
	```
</details>
<details><summary><b><a href="https://github.com/yezyilomo/django-restql">django-restql</a></b> (🥉23 ·  ⭐ 620 · ➕) - Turn your API made with Django REST Framework(DRF) into a GraphQL like API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/yezyilomo/django-restql) (👨‍💻 5 · 🔀 44 · 📦 270 · 📋 110 - 22% open · ⏱️ 25.01.2024):

	```
	git clone https://github.com/yezyilomo/django-restql
	```
- [PyPi](https://pypi.org/project/django-restql) (📥 34K / month):
	```
	pip install django-restql
	```
</details>
<details><summary><b><a href="https://github.com/wq/django-rest-pandas">django-rest-pandas</a></b> (🥉17 ·  ⭐ 1.2K · ➕) - Serves up Pandas dataframes via the Django REST Framework for use in client-side (i.e. d3.js) visualizations and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wq/django-rest-pandas) (👨‍💻 3 · 🔀 120 · 📋 40 - 20% open · ⏱️ 04.04.2024):

	```
	git clone https://github.com/wq/django-rest-pandas
	```
- [PyPi](https://pypi.org/project/django-rest-pandas):
	```
	pip install django-rest-pandas
	```
</details>
<br>

## RESTful API (Django Ninja)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/vitalik/django-ninja">django-ninja</a></b> (🥇30 ·  ⭐ 6.9K) - Fast, Async-ready, Openapi, type hints based framework for building APIs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vitalik/django-ninja) (👨‍💻 140 · 🔀 410 · 📋 820 - 35% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/vitalik/django-ninja
	```
- [PyPi](https://pypi.org/project/django-ninja) (📥 450K / month):
	```
	pip install django-ninja
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-extra">django-ninja-extra</a></b> (🥈23 ·  ⭐ 360) - Django Ninja Extra - Class-Based Utility and more for Django Ninja(Fast Django REST framework). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-extra) (👨‍💻 16 · 🔀 28 · 📋 57 - 19% open · ⏱️ 03.09.2024):

	```
	git clone https://github.com/eadwinCode/django-ninja-extra
	```
- [PyPi](https://pypi.org/project/django-ninja-extra) (📥 88K / month):
	```
	pip install django-ninja-extra
	```
</details>
<details><summary><b><a href="https://github.com/eadwinCode/django-ninja-jwt">django-ninja-jwt</a></b> (🥈22 ·  ⭐ 130) - A JSON Web Token authentication plugin for the Django REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eadwinCode/django-ninja-jwt) (👨‍💻 84 · 🔀 20 · 📦 230 · 📋 26 - 38% open · ⏱️ 21.08.2024):

	```
	git clone https://github.com/eadwinCode/django-ninja-jwt
	```
- [PyPi](https://pypi.org/project/django-ninja-jwt) (📥 45K / month):
	```
	pip install django-ninja-jwt
	```
</details>
<details><summary><b><a href="https://github.com/mawassk/django-ninja-apikey">django-ninja-apikey</a></b> (🥉12 ·  ⭐ 40 · 💤) - Easy to use API key authentication for Django Ninja REST Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mawassk/django-ninja-apikey) (🔀 10 · 📦 5 · 📋 3 - 66% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/mawassk/django-ninja-apikey
	```
- [PyPi](https://pypi.org/project/django-ninja-apikey) (📥 1.2K / month):
	```
	pip install django-ninja-apikey
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/eadwinCode/django-ninja-passwordreset">django-ninja-passwordreset</a></b> (🥉12 ·  ⭐ 5) - An extension of django rest framework, providing a configurable password reset strategy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mugartec/django-ninja-auth">django-ninja-auth</a></b> (🥉7 ·  ⭐ 29 · 💤) -  <code><a href="https://tldrlegal.com/search?q=WTFPL">❗️WTFPL</a></code>
</details>
<br>

## Pydantic integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pydantic/pydantic">pydantic</a></b> (🥇47 ·  ⭐ 20K) - Data validation using Python type hints. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydantic/pydantic) (👨‍💻 570 · 🔀 1.8K · 📦 490K · 📋 4.4K - 9% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/pydantic/pydantic
	```
- [PyPi](https://pypi.org/project/pydantic) (📥 250M / month):
	```
	pip install pydantic
	```
</details>
<details><summary><b><a href="https://github.com/jordaneremieff/djantic">djantic</a></b> (🥈20 ·  ⭐ 460 · 💤) - Pydantic model support for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jordaneremieff/djantic) (👨‍💻 4 · 🔀 34 · 📦 76 · 📋 41 - 31% open · ⏱️ 13.02.2023):

	```
	git clone https://github.com/jordaneremieff/djantic
	```
- [PyPi](https://pypi.org/project/djantic) (📥 10K / month):
	```
	pip install djantic
	```
</details>
<details><summary><b><a href="https://github.com/yezz123/pyngo">pyngo</a></b> (🥉19 ·  ⭐ 81) - Pydantic model support for Django & Django-Rest-Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/yezz123/pyngo) (👨‍💻 8 · 🔀 8 · 📦 14 · 📋 4 - 25% open · ⏱️ 26.08.2024):

	```
	git clone https://github.com/yezz123/pyngo
	```
- [PyPi](https://pypi.org/project/pyngo) (📥 4.8K / month):
	```
	pip install pyngo
	```
</details>
<details><summary><b><a href="https://github.com/jonathan-s/djantic2">djantic2</a></b> (🥉18 ·  ⭐ 43 · 🐣) - Pydantic model support for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jonathan-s/djantic2) (👨‍💻 8 · 🔀 6 · 📦 3 · 📋 7 - 28% open · ⏱️ 14.07.2024):

	```
	git clone https://github.com/jonathan-s/djantic2
	```
- [PyPi](https://pypi.org/project/djantic) (📥 10K / month):
	```
	pip install djantic
	```
</details>
<br>

## Pandas integration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/chrisdev/django-pandas">django-pandas</a></b> (🥇24 ·  ⭐ 800) - Tools for working with pandas in your Django projects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/chrisdev/django-pandas) (👨‍💻 35 · 🔀 110 · 📦 2.4K · 📋 85 - 16% open · ⏱️ 03.04.2024):

	```
	git clone https://github.com/chrisdev/django-pandas
	```
- [PyPi](https://pypi.org/project/django-pandas) (📥 120K / month):
	```
	pip install django-pandas
	```
</details>
<br>

## GraphQL API

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages to implement GraphQL API._

<details><summary><b><a href="https://github.com/graphql-python/graphene">graphene</a></b> (🥇37 ·  ⭐ 8.1K) - GraphQL framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene) (👨‍💻 210 · 🔀 800 · 📦 23K · 📋 1K - 9% open · ⏱️ 08.08.2024):

	```
	git clone https://github.com/graphql-python/graphene
	```
- [PyPi](https://pypi.org/project/graphene) (📥 10M / month):
	```
	pip install graphene
	```
</details>
<details><summary><b><a href="https://github.com/graphql-python/graphene-django">graphene-django</a></b> (🥈33 ·  ⭐ 4.3K) - Build powerful, efficient, and flexible GraphQL APIs with seamless Django integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/graphql-python/graphene-django) (👨‍💻 220 · 🔀 740 · 📦 15K · 📋 820 - 17% open · ⏱️ 12.06.2024):

	```
	git clone https://github.com/graphql-python/graphene-django
	```
- [PyPi](https://pypi.org/project/graphene-django) (📥 760K / month):
	```
	pip install graphene-django
	```
</details>
<details><summary><b><a href="https://github.com/mirumee/ariadne">ariadne</a></b> (🥈32 ·  ⭐ 2.2K · ➕) - Python library for implementing GraphQL servers using schema-first approach. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mirumee/ariadne) (👨‍💻 76 · 🔀 180 · 📦 1.7K · 📋 310 - 9% open · ⏱️ 02.08.2024):

	```
	git clone https://github.com/mirumee/ariadne
	```
- [PyPi](https://pypi.org/project/ariadne) (📥 260K / month):
	```
	pip install ariadne
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry-django">strawberry-graphql-django</a></b> (🥉29 ·  ⭐ 400) - Strawberry GraphQL Django extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry-django) (👨‍💻 86 · 🔀 120 · 📦 480 · 📋 310 - 22% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/strawberry-graphql/strawberry-graphql-django
	```
- [PyPi](https://pypi.org/project/strawberry-graphql-django) (📥 110K / month):
	```
	pip install strawberry-graphql-django
	```
</details>
<details><summary><b><a href="https://github.com/flavors/django-graphql-jwt">django-graphql-jwt</a></b> (🥉28 ·  ⭐ 820 · 💤) - JSON Web Token (JWT) authentication for Graphene Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/flavors/django-graphql-jwt) (👨‍💻 26 · 🔀 150 · 📦 5.2K · 📋 230 - 26% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/flavors/django-graphql-jwt
	```
- [PyPi](https://pypi.org/project/django-graphql-jwt) (📥 110K / month):
	```
	pip install django-graphql-jwt
	```
</details>
<details><summary><b><a href="https://github.com/strawberry-graphql/strawberry">strawberry</a></b> (🥉27 ·  ⭐ 3.9K) - A GraphQL library for Python that leverages type annotations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/strawberry-graphql/strawberry) (👨‍💻 260 · 🔀 510 · 📥 420 · 📋 1K - 39% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/strawberry-graphql/strawberry
	```
- [PyPi](https://pypi.org/project/strawberry) (📥 500 / month):
	```
	pip install strawberry
	```
</details>
<details><summary><b><a href="https://github.com/PedroBern/django-graphql-auth">django-graphql-auth</a></b> (🥉21 ·  ⭐ 330 · 💤) - Django registration and authentication with GraphQL. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PedroBern/django-graphql-auth) (👨‍💻 16 · 🔀 100 · 📦 720 · 📋 100 - 58% open · ⏱️ 17.06.2022):

	```
	git clone https://github.com/PedroBern/django-graphql-auth
	```
- [PyPi](https://pypi.org/project/django-graphql-auth) (📥 16K / month):
	```
	pip install django-graphql-auth
	```
</details>
<details><summary><b><a href="https://github.com/mirumee/ariadne-django">ariadne-django</a></b> (🥉14 ·  ⭐ 63 · 💤) - ariadne_django makes integrating ariadne and django together easier. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mirumee/ariadne-django) (👨‍💻 9 · 🔀 11 · 📋 27 - 40% open · ⏱️ 23.08.2022):

	```
	git clone https://github.com/mirumee/ariadne-django
	```
- [PyPi](https://pypi.org/project/ariadne-django) (📥 15K / month):
	```
	pip install ariadne-django
	```
</details>
<br>

## Feature Flipper

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/django-waffle">django-waffle</a></b> (🥇31 ·  ⭐ 1.1K) - A feature flipper for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-waffle) (👨‍💻 120 · 🔀 240 · 📦 1.4K · 📋 210 - 20% open · ⏱️ 05.08.2024):

	```
	git clone https://github.com/django-waffle/django-waffle
	```
- [PyPi](https://pypi.org/project/django-waffle) (📥 520K / month):
	```
	pip install django-waffle
	```
</details>
<br>

## Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Packages which add application layer statistic functionality._

<details><summary><b><a href="https://github.com/pennersr/django-trackstats">django-trackstats</a></b> (🥇15 ·  ⭐ 440 · 💤) - Keep track of your statistics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pennersr/django-trackstats) (👨‍💻 9 · 🔀 39 · 📦 25 · 📋 12 - 33% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/pennersr/django-trackstats
	```
- [PyPi](https://pypi.org/project/django-trackstats) (📥 4.6K / month):
	```
	pip install django-trackstats
	```
</details>
<br>

## Testing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pytest-dev/pytest-django">pytest-django</a></b> (🥇37 ·  ⭐ 1.4K) - A Django plugin for pytest. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-django) (👨‍💻 150 · 🔀 330 · 📦 80K · 📋 530 - 27% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/pytest-dev/pytest-django
	```
- [PyPi](https://pypi.org/project/pytest-django) (📥 4.9M / month):
	```
	pip install pytest-django
	```
</details>
<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model_bakery</a></b> (🥈28 ·  ⭐ 820) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 57 · 🔀 84 · 📦 4.4K · 📋 140 - 19% open · ⏱️ 26.08.2024):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model_bakery) (📥 790K / month):
	```
	pip install model_bakery
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/django-test-migrations">django-test-migrations</a></b> (🥉26 ·  ⭐ 520) - Test django schema and data migrations, including migrations order and best practices. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/django-test-migrations) (👨‍💻 18 · 🔀 31 · 📦 780 · 📋 65 - 23% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/wemake-services/django-test-migrations
	```
- [PyPi](https://pypi.org/project/django-test-migrations) (📥 200K / month):
	```
	pip install django-test-migrations
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥉25 ·  ⭐ 3.5K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 130 · 🔀 380 · 📋 580 - 25% open · ⏱️ 18.08.2024):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 5.3M / month):
	```
	pip install factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/revsys/django-test-plus">django-test-plus</a></b> (🥉20 ·  ⭐ 610) - Useful additions to Djangos default TestCase. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/revsys/django-test-plus) (👨‍💻 35 · 🔀 61 · 📋 57 - 10% open · ⏱️ 11.08.2024):

	```
	git clone https://github.com/revsys/django-test-plus
	```
- [PyPi](https://pypi.org/project/django-test-plus) (📥 61K / month):
	```
	pip install django-test-plus
	```
</details>
<br>

## Monitoring frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Monitoring (Application Performance Monitoring, ...) frameworks which use Django under the hood._

<br>

## CMS frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Content Management Systems which use Django under the hood._

<details><summary><b><a href="https://github.com/wagtail/wagtail">wagtail</a></b> (🥇43 ·  ⭐ 18K · 📈) - A Django content management system focused on flexibility and user experience. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wagtail/wagtail) (👨‍💻 930 · 🔀 3.7K · 📦 11K · 📋 5K - 16% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/wagtail/wagtail
	```
- [PyPi](https://pypi.org/project/wagtail) (📥 520K / month):
	```
	pip install wagtail
	```
</details>
<details><summary><b><a href="https://github.com/django-cms/django-cms">django-cms</a></b> (🥉41 ·  ⭐ 10K) - The easy-to-use and developer-friendly enterprise CMS powered by Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-cms/django-cms) (👨‍💻 570 · 🔀 3K · 📦 5.3K · 📋 3.5K - 3% open · ⏱️ 29.08.2024):

	```
	git clone https://github.com/django-cms/django-cms
	```
- [PyPi](https://pypi.org/project/django-cms) (📥 69K / month):
	```
	pip install django-cms
	```
</details>
<details><summary><b><a href="https://github.com/stephenmcd/mezzanine">mezzanine</a></b> (🥉26 ·  ⭐ 4.8K · 💤) - CMS framework for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/stephenmcd/mezzanine) (👨‍💻 330 · 🔀 1.6K · 📋 1.1K - 3% open · ⏱️ 02.11.2022):

	```
	git clone https://github.com/stephenmcd/mezzanine
	```
- [PyPi](https://pypi.org/project/mezzanine) (📥 5.1K / month):
	```
	pip install mezzanine
	```
</details>
<br>

## E-Commerce frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_E-Commerce frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/django-oscar/django-oscar">django-oscar</a></b> (🥇36 ·  ⭐ 6.2K) - Domain-driven e-commerce for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-oscar/django-oscar) (👨‍💻 370 · 🔀 2.2K · 📦 1.1K · 📋 1.5K - 5% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/django-oscar/django-oscar
	```
- [PyPi](https://pypi.org/project/django-oscar) (📥 27K / month):
	```
	pip install django-oscar
	```
</details>
<details><summary><b><a href="https://github.com/saleor/saleor">saleor</a></b> (🥈34 ·  ⭐ 21K) - Saleor Core: the high performance, composable, headless commerce API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/saleor/saleor) (👨‍💻 290 · 🔀 5.3K · 📥 560 · 📦 4 · 📋 4.3K - 13% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/saleor/saleor
	```
- [PyPi](https://pypi.org/project/saleor) (📥 27 / month):
	```
	pip install saleor
	```
</details>
<details><summary><b><a href="https://github.com/awesto/django-shop">django-shop</a></b> (🥉26 ·  ⭐ 3.2K · 💤) - A Django based shop system. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/awesto/django-shop) (👨‍💻 96 · 🔀 990 · 📦 230 · 📋 380 - 23% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/awesto/django-shop
	```
- [PyPi](https://pypi.org/project/django-shop) (📥 2.5K / month):
	```
	pip install django-shop
	```
</details>
<details><summary><b><a href="https://github.com/shuup/shuup">shuup</a></b> (🥉24 ·  ⭐ 2.2K · 💤) - E-Commerce Platform. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/shuup/shuup) (👨‍💻 67 · 🔀 1.1K · 📥 600 · 📦 170 · 📋 440 - 33% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/shuup/shuup
	```
- [PyPi](https://pypi.org/project/shuup) (📥 6.7K / month):
	```
	pip install shuup
	```
</details>
<br>

## Analytics frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Analytics frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/milesmcc/shynet">shynet</a></b> (🥇19 ·  ⭐ 2.9K) - Modern, privacy-friendly, and detailed web analytics that works without cookies or JS. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milesmcc/shynet) (👨‍💻 37 · 🔀 180 · 📋 190 - 24% open · ⏱️ 05.06.2024):

	```
	git clone https://github.com/milesmcc/shynet
	```
- [PyPi](https://pypi.org/project/shynet):
	```
	pip install shynet
	```
</details>
<br>

## Project management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Project management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/makeplane/plane">plane</a></b> (🥇25 ·  ⭐ 29K) - Open Source JIRA, Linear, Monday, and Asana Alternative. Plane helps you track your issues, epics, and product.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/makeplane/plane) (👨‍💻 92 · 🔀 1.5K · 📋 930 - 38% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/makeplane/plane
	```
</details>
<details><summary><b><a href="https://github.com/kaleidos-ventures/taiga">taiga</a></b> (🥉12 ·  ⭐ 440) - Taiga is a free and open-source project management for cross-functional agile teams. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/kaleidos-ventures/taiga) (👨‍💻 11 · 🔀 57 · ⏱️ 13.12.2023):

	```
	git clone https://github.com/kaleidos-ventures/taiga
	```
</details>
<br>

## Monitoring frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Monitoring frameworks which use Django under the hood._

<br>

## Photo management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Photo management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/LibrePhotos/librephotos">librephotos</a></b> (🥇21 ·  ⭐ 6.8K) - A self-hosted open source photo management service. This is the repository of the backend. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/LibrePhotos/librephotos) (👨‍💻 75 · 🔀 300 · 📋 860 - 31% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/LibrePhotos/librephotos
	```
</details>
<br>

## Recipe management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Recipe management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/TandoorRecipes/recipes">Tandoor Recipes</a></b> (🥇24 ·  ⭐ 5.3K) - Application for managing recipes, planning meals, building shopping lists and much much more!. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/TandoorRecipes/recipes) (👨‍💻 360 · 🔀 550 · 📋 1.7K - 16% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/TandoorRecipes/recipes
	```
</details>
<br>

## Document management frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Document management frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/paperless-ngx/paperless-ngx">Paperless-ngx</a></b> (🥇31 ·  ⭐ 19K) - A community-supported supercharged version of paperless: scan, index and archive all your physical documents. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/paperless-ngx/paperless-ngx) (👨‍💻 360 · 🔀 1K · 📥 99K · ⏱️ 05.09.2024):

	```
	git clone https://github.com/paperless-ngx/paperless-ngx
	```
</details>
<br>

## Education frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Education frameworks which use Django under the hood._

<details><summary><b><a href="https://github.com/openedx/edx-platform">Open edX</a></b> (🥇29 ·  ⭐ 7.2K) - The Open edX LMS & Studio, powering education sites around the world!. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/openedx/edx-platform) (👨‍💻 1.4K · 🔀 3.5K · 📦 3 · 📋 590 - 35% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/openedx/edx-platform
	```
</details>
<br>

## Inventory management system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Inventory management systems which use Django under the hood._

<details><summary><b><a href="https://github.com/inventree/InvenTree">InvenTree</a></b> (🥇27 ·  ⭐ 4.1K) - Open Source Inventory Management System. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inventree/InvenTree) (👨‍💻 92 · 🔀 710 · 📥 600 · 📋 2.6K - 8% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/inventree/InvenTree
	```
</details>
<br>

## Crawler management system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Web crawler management systems which use Django under the hood._

<br>

## Network automation system based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Network automation systems which use Django under the hood._

<details><summary><b><a href="https://github.com/netbox-community/netbox">netbox</a></b> (🥇32 ·  ⭐ 16K) - The premier source of truth powering network automation. Open source under Apache 2. Public demo:.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/netbox-community/netbox) (👨‍💻 370 · 🔀 2.5K · 📋 10K - 3% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/netbox-community/netbox
	```
</details>
<br>

## Fields (encrypted)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/georgemarshall/django-cryptography">django-cryptography</a></b> (🥇19 ·  ⭐ 380) - Easily encrypt data in Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/georgemarshall/django-cryptography) (👨‍💻 4 · 🔀 70 · 📋 73 - 56% open · ⏱️ 16.02.2024):

	```
	git clone https://github.com/georgemarshall/django-cryptography
	```
- [PyPi](https://pypi.org/project/django-cryptography) (📥 170K / month):
	```
	pip install django-cryptography
	```
</details>
<details><summary><b><a href="https://github.com/luojilab/django-mirage-field">django-mirage-field</a></b> (🥈17 ·  ⭐ 93 · 💤) - Django model field encrypt/decrypt your data, keep secret in database. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/luojilab/django-mirage-field) (👨‍💻 9 · 🔀 13 · 📦 87 · 📋 14 - 14% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/luojilab/django-mirage-field
	```
- [PyPi](https://pypi.org/project/django-mirage-field) (📥 18K / month):
	```
	pip install django-mirage-field
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/orcasgit/django-fernet-fields">django-fernet-fields</a></b> (🥈18 ·  ⭐ 190 · 💀) - Fernet symmetric encryption for Django model fields. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/foundertherapy/django-cryptographic-fields">django-cryptographic-fields</a></b> (🥉14 ·  ⭐ 29 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/lansharkconsulting/django/django-encrypted-model-fields">django-encrypted-model-fields</a></b> (🥉11 ·  ⭐ 33 · 💀) - A set of fields that wrap standard Django fields with encryption provided by the python cryptography library. <code>❗Unlicensed</code>
- <b><a href="https://gitlab.com/guywillett/django-searchable-encrypted-fields">django-searchable-encrypted-fields</a></b> (🥉6 ·  ⭐ 9 · 💀) -  <code>❗Unlicensed</code>
</details>
<br>

## Fields (phone numbers)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/stefanfoulis/django-phonenumber-field">django-phonenumber-field</a></b> (🥇35 ·  ⭐ 1.5K) - A django model and form field for normalised phone numbers using python-phonenumbers. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-phonenumber-field) (👨‍💻 120 · 🔀 300 · 📥 25 · 📦 28K · 📋 220 - 2% open · ⏱️ 19.07.2024):

	```
	git clone https://github.com/stefanfoulis/django-phonenumber-field
	```
- [PyPi](https://pypi.org/project/django-phonenumber-field) (📥 1.3M / month):
	```
	pip install django-phonenumber-field
	```
</details>
<details><summary><b><a href="https://github.com/VeryApt/django-phone-field">django-phone-field</a></b> (🥉18 ·  ⭐ 52 · 💤) - Lightweight model and form field for phone numbers in Django. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/VeryApt/django-phone-field) (👨‍💻 4 · 🔀 13 · 📦 3.1K · 📋 15 - 26% open · ⏱️ 10.06.2020):

	```
	git clone https://github.com/VeryApt/django-phone-field
	```
- [PyPi](https://pypi.org/project/django-phone-field) (📥 26K / month):
	```
	pip install django-phone-field
	```
</details>
<br>

## Fields (addresses)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/furious-luke/django-address">django-address</a></b> (🥇24 ·  ⭐ 430 · 💤) - A Django address model and field. Addresses may be specified by address components or by performing an automatic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/furious-luke/django-address) (👨‍💻 22 · 🔀 160 · 📦 440 · 📋 130 - 32% open · ⏱️ 05.05.2022):

	```
	git clone https://github.com/furious-luke/django-address
	```
- [PyPi](https://pypi.org/project/django-address) (📥 13K / month):
	```
	pip install django-address
	```
</details>
<details><summary><b><a href="https://github.com/openwisp/django-loci">django-loci</a></b> (🥈23 ·  ⭐ 180) - Reusable Django app for storing geographic and indoor coordinates. Maintained by the OpenWISP Project. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/openwisp/django-loci) (👨‍💻 30 · 🔀 40 · 📦 12 · 📋 41 - 4% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/openwisp/django-loci
	```
- [PyPi](https://pypi.org/project/django-loci) (📥 1.3K / month):
	```
	pip install django-loci
	```
</details>
<details><summary><b><a href="https://github.com/madisona/django-google-maps">django-google-maps</a></b> (🥉21 ·  ⭐ 280 · 💤) - Using the Google Maps API with django model admin. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madisona/django-google-maps) (👨‍💻 19 · 🔀 93 · 📦 670 · 📋 47 - 25% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/madisona/django-google-maps
	```
- [PyPi](https://pypi.org/project/django-google-maps) (📥 9.1K / month):
	```
	pip install django-google-maps
	```
</details>
<details><summary><b><a href="https://github.com/simon-the-shark/django-mapbox-location-field">django-mapbox-location-field</a></b> (🥉19 ·  ⭐ 66 · 📉) - Simple in use location model and form field with MapInput widget for picking some location. Uses mapbox gl js,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/simon-the-shark/django-mapbox-location-field) (👨‍💻 8 · 🔀 22 · 📦 380 · 📋 27 - 14% open · ⏱️ 20.06.2024):

	```
	git clone https://github.com/Simon-the-Shark/django-mapbox-location-field
	```
- [PyPi](https://pypi.org/project/django-mapbox-location-field) (📥 1.4K / month):
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

<details><summary><b><a href="https://github.com/etianen/django-reversion">django-reversion</a></b> (🥇36 ·  ⭐ 3K) - django-reversion is an extension to the Django web framework that provides version control for model instances. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/etianen/django-reversion) (👨‍💻 190 · 🔀 460 · 📦 7.5K · 📋 650 - 2% open · ⏱️ 09.08.2024):

	```
	git clone https://github.com/etianen/django-reversion
	```
- [PyPi](https://pypi.org/project/django-reversion) (📥 510K / month):
	```
	pip install django-reversion
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-simple-history">django-simple-history</a></b> (🥈35 ·  ⭐ 2.2K · 📉) - Store model history and view/revert changes from admin site. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/django-simple-history) (👨‍💻 180 · 🔀 450 · 📦 5.7K · 📋 580 - 23% open · ⏱️ 22.07.2024):

	```
	git clone https://github.com/jazzband/django-simple-history
	```
- [PyPi](https://pypi.org/project/django-simple-history) (📥 1.2M / month):
	```
	pip install django-simple-history
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-auditlog">django-auditlog</a></b> (🥈31 ·  ⭐ 1.1K) - A Django app that keeps a log of changes made to an object. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jazzband/django-auditlog) (👨‍💻 81 · 🔀 370 · 📥 390 · 📦 1.1K · 📋 280 - 23% open · ⏱️ 01.08.2024):

	```
	git clone https://github.com/jazzband/django-auditlog
	```
- [PyPi](https://pypi.org/project/django-auditlog) (📥 360K / month):
	```
	pip install django-auditlog
	```
</details>
<details><summary><b><a href="https://github.com/soynatan/django-easy-audit">django-easy-audit</a></b> (🥉24 ·  ⭐ 710) - Yet another Django audit log app, hopefully the simplest one. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/soynatan/django-easy-audit) (👨‍💻 48 · 🔀 170 · 📦 290 · 📋 150 - 50% open · ⏱️ 30.08.2024):

	```
	git clone https://github.com/soynatan/django-easy-audit
	```
- [PyPi](https://pypi.org/project/django-easy-audit) (📥 49K / month):
	```
	pip install django-easy-audit
	```
</details>
<details><summary><b><a href="https://github.com/romgar/django-dirtyfields">django-dirtyfields</a></b> (🥉23 ·  ⭐ 620 · 📈) - Tracking dirty fields on a Django model. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/romgar/django-dirtyfields) (👨‍💻 42 · 🔀 98 · 📦 590 · 📋 71 - 15% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/romgar/django-dirtyfields
	```
- [PyPi](https://pypi.org/project/django-dirtyfields) (📥 260K / month):
	```
	pip install django-dirtyfields
	```
</details>
<details><summary><b><a href="https://github.com/craigds/django-fieldsignals">django-fieldsignals</a></b> (🥉16 ·  ⭐ 110 · 💤) - Django signals for changed fields. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/craigds/django-fieldsignals) (👨‍💻 5 · 🔀 11 · 📦 270 · 📋 17 - 17% open · ⏱️ 08.10.2022):

	```
	git clone https://github.com/craigds/django-fieldsignals
	```
- [PyPi](https://pypi.org/project/django-fieldsignals) (📥 20K / month):
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

<details><summary><b><a href="https://github.com/lamby/django-slack">django-slack</a></b> (🥇22 ·  ⭐ 240) - Slack integration for Django, using the templating engine to generate messages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lamby/django-slack) (👨‍💻 29 · 🔀 55 · 📦 400 · 📋 63 - 14% open · ⏱️ 10.05.2024):

	```
	git clone https://github.com/lamby/django-slack
	```
- [PyPi](https://pypi.org/project/django-slack) (📥 90K / month):
	```
	pip install django-slack
	```
</details>
<details><summary><b><a href="https://github.com/stefanfoulis/django-sendsms">django-sendsms</a></b> (🥈17 ·  ⭐ 260 · 💤) - A simple API to send SMS messages. It is modeled after the django email api. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanfoulis/django-sendsms) (👨‍💻 19 · 🔀 90 · 📦 380 · 📋 24 - 20% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/stefanfoulis/django-sendsms
	```
- [PyPi](https://pypi.org/project/django-sendsms) (📥 4.8K / month):
	```
	pip install django-sendsms
	```
</details>
<details><summary><b><a href="https://github.com/roaldnefs/django-sms">django-sms</a></b> (🥉13 ·  ⭐ 52) - A Django app for sending SMS with interchangeable backends. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/roaldnefs/django-sms) (👨‍💻 3 · 🔀 14 · 📋 15 - 40% open · ⏱️ 07.01.2024):

	```
	git clone https://github.com/roaldnefs/django-sms
	```
- [PyPi](https://pypi.org/project/django-sms) (📥 10K / month):
	```
	pip install django-sms
	```
</details>
<details><summary><b><a href="https://github.com/Ninjaclasher/django-discord-integration">django-discord-integration</a></b> (🥉10 ·  ⭐ 22) - Discord integration for Django, supporting error reporting via webhooks. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/Ninjaclasher/django-discord-integration) (👨‍💻 2 · 🔀 1 · 📦 6 · ⏱️ 28.05.2024):

	```
	git clone https://github.com/Ninjaclasher/django-discord-integration
	```
- [PyPi](https://pypi.org/project/django-discord-integration) (📥 920 / month):
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

<details><summary><b><a href="https://github.com/jschneier/django-storages">django-storages</a></b> (🥇36 ·  ⭐ 2.7K) - https://django-storages.readthedocs.io/. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jschneier/django-storages) (👨‍💻 270 · 🔀 810 · 📦 180K · 📋 710 - 13% open · ⏱️ 25.08.2024):

	```
	git clone https://github.com/jschneier/django-storages
	```
- [PyPi](https://pypi.org/project/django-storages) (📥 4.2M / month):
	```
	pip install django-storages
	```
</details>
<details><summary><b><a href="https://github.com/py-pa/django-minio-storage">django-minio-storage</a></b> (🥉21 ·  ⭐ 150) - A django storage driver for minio. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py-pa/django-minio-storage) (👨‍💻 18 · 🔀 53 · 📦 300 · 📋 82 - 13% open · ⏱️ 19.12.2023):

	```
	git clone https://github.com/py-pa/django-minio-storage
	```
- [PyPi](https://pypi.org/project/django-minio-storage) (📥 25K / month):
	```
	pip install django-minio-storage
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/maddevsio/django_minio">django-minio</a></b> (🥉7 ·  ⭐ 65 · 💀) - Django app to use Minio Server as file storage. <code>❗Unlicensed</code>
</details>
<br>

## Event Sourcing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing">eventsourcing</a></b> (🥇25 ·  ⭐ 1.4K) - A library for event sourcing in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing) (👨‍💻 27 · 🔀 130 · 📦 160 · 📋 90 - 2% open · ⏱️ 22.08.2024):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing
	```
- [PyPi](https://pypi.org/project/eventsourcing) (📥 11K / month):
	```
	pip install eventsourcing
	```
</details>
<details><summary><b><a href="https://github.com/pyeventsourcing/eventsourcing-django">eventsourcing-django</a></b> (🥈11 ·  ⭐ 39 · 💤) - Python package for eventsourcing with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyeventsourcing/eventsourcing-django) (👨‍💻 5 · 🔀 10 · 📦 7 · 📋 4 - 50% open · ⏱️ 16.03.2023):

	```
	git clone https://github.com/pyeventsourcing/eventsourcing-django
	```
- [PyPi](https://pypi.org/project/eventsourcing-django) (📥 1.4K / month):
	```
	pip install eventsourcing-django
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/pyeventsourcing/eventsourcing-eventstoredb">eventsourcing-eventstoredb</a></b> (🥉7 ·  ⭐ 16) - Python package for eventsourcing with EventStoreDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-dynamodb">eventsourcing-dynamodb</a></b> (🥉4 ·  ⭐ 4 · 💤) - Python package for eventsourcing with DynamoDB. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pyeventsourcing/eventsourcing-axonserver">eventsourcing-axonserver</a></b> (🥉4 ·  ⭐ 2 · 💤) - Python package for eventsourcing with Axon Server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Locking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/saxix/django-concurrency">django-concurrency</a></b> (🥇21 ·  ⭐ 430) - Optimistic lock implementation for Django. Prevents users from doing concurrent editing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/saxix/django-concurrency) (👨‍💻 25 · 🔀 50 · 📦 180 · 📋 73 - 6% open · ⏱️ 30.07.2024):

	```
	git clone https://github.com/saxix/django-concurrency
	```
- [PyPi](https://pypi.org/project/django-concurrency) (📥 51K / month):
	```
	pip install django-concurrency
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/gavinwahl/django-optimistic-lock">django-optimistic-lock</a></b> (🥉14 ·  ⭐ 120 · 💀) - Offline optimistic locking for Django. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/debrouwere/django-locking">django-locking</a></b> (🥉8 ·  ⭐ 140 · 💀) - Prevents users from doing concurrent editing in Django. Works out of the box in the admin interface, or you can.. <code>❗Unlicensed</code>
</details>
<br>

## Example data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Brobin/django-seed">django-seed</a></b> (🥇25 ·  ⭐ 680 · 💤) - Seed your Django database with fake data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Brobin/django-seed) (👨‍💻 23 · 🔀 80 · 📦 4.7K · 📋 58 - 27% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/brobin/django-seed
	```
- [PyPi](https://pypi.org/project/django-seed) (📥 29K / month):
	```
	pip install django-seed
	```
</details>
<details><summary><b><a href="https://github.com/davedash/django-fixture-magic">django-fixture-magic</a></b> (🥉19 ·  ⭐ 390) - Utilities to extract and manipulate Django Fixtures. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/davedash/django-fixture-magic) (👨‍💻 36 · 🔀 91 · 📦 160 · 📋 35 - 34% open · ⏱️ 26.10.2023):

	```
	git clone https://github.com/davedash/django-fixture-magic
	```
- [PyPi](https://pypi.org/project/django-fixture-magic) (📥 26K / month):
	```
	pip install django-fixture-magic
	```
</details>
<details><summary><b><a href="https://github.com/klen/mixer">mixer</a></b> (🥉16 ·  ⭐ 940 · 💤) - Mixer -- Is a fixtures replacement. Supported Django, Flask, SqlAlchemy and custom python objects. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/klen/mixer) (👨‍💻 43 · 🔀 93 · 📋 87 - 43% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/klen/mixer
	```
- [PyPi](https://pypi.org/project/mixer) (📥 140K / month):
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

<details><summary><b><a href="https://github.com/model-bakers/model_bakery">model-bakery</a></b> (🥇28 ·  ⭐ 820) - Object factory for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/model-bakers/model_bakery) (👨‍💻 57 · 🔀 84 · 📦 4.4K · 📋 140 - 19% open · ⏱️ 26.08.2024):

	```
	git clone https://github.com/model-bakers/model_bakery
	```
- [PyPi](https://pypi.org/project/model-bakery/) (📥 790K / month):
	```
	pip install model-bakery/
	```
</details>
<details><summary><b><a href="https://github.com/paulocheque/django-dynamic-fixture">django-dynamic-fixture</a></b> (🥉22 ·  ⭐ 390) - A complete library to create dynamic model instances for testing purposes. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/paulocheque/django-dynamic-fixture) (👨‍💻 37 · 🔀 62 · 📦 1.2K · 📋 69 - 7% open · ⏱️ 30.07.2024):

	```
	git clone https://github.com/paulocheque/django-dynamic-fixture
	```
- [PyPi](https://pypi.org/project/django-dynamic-fixture) (📥 89K / month):
	```
	pip install django-dynamic-fixture
	```
</details>
<br>

## Bootstrap CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/zostera/django-bootstrap4">django-bootstrap4</a></b> (🥇32 ·  ⭐ 1K) - Bootstrap 4 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap4) (👨‍💻 140 · 🔀 220 · 📦 160K · 📋 160 - 10% open · ⏱️ 25.04.2024):

	```
	git clone https://github.com/zostera/django-bootstrap4
	```
- [PyPi](https://pypi.org/project/django-bootstrap4) (📥 170K / month):
	```
	pip install django-bootstrap4
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap3">django-bootstrap3</a></b> (🥈30 ·  ⭐ 2.3K) - Bootstrap 3 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap3) (👨‍💻 99 · 🔀 670 · 📦 19K · ⏱️ 11.08.2024):

	```
	git clone https://github.com/zostera/django-bootstrap3
	```
- [PyPi](https://pypi.org/project/django-bootstrap3) (📥 120K / month):
	```
	pip install django-bootstrap3
	```
</details>
<details><summary><b><a href="https://github.com/zostera/django-bootstrap5">django-bootstrap5</a></b> (🥉27 ·  ⭐ 380) - Bootstrap 5 for Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zostera/django-bootstrap5) (👨‍💻 150 · 🔀 82 · 📦 7.1K · 📋 97 - 31% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/zostera/django-bootstrap5
	```
- [PyPi](https://pypi.org/project/django-bootstrap5) (📥 120K / month):
	```
	pip install django-bootstrap5
	```
</details>
<details><summary><b><a href="https://github.com/zelenij/django-bootstrap-v5">django-bootstrap-v5</a></b> (🥉21 ·  ⭐ 100) - Bootstrap 5 integration with Django. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/zelenij/django-bootstrap-v5) (👨‍💻 140 · 🔀 44 · 📦 8.6K · 📋 23 - 34% open · ⏱️ 07.01.2024):

	```
	git clone https://github.com/zelenij/django-bootstrap-v5
	```
- [PyPi](https://pypi.org/project/django-bootstrap-v5) (📥 53K / month):
	```
	pip install django-bootstrap-v5
	```
</details>
<br>

## Bulma CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/timonweb/django-bulma">django-bulma</a></b> (🥇18 ·  ⭐ 340) - Bulma theme for Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/django-bulma) (👨‍💻 15 · 🔀 56 · 📦 510 · 📋 43 - 11% open · ⏱️ 26.06.2024):

	```
	git clone https://github.com/timonweb/django-bulma
	```
- [PyPi](https://pypi.org/project/django-bulma) (📥 3.8K / month):
	```
	pip install django-bulma
	```
</details>
<br>

## TailwindCSS CSS Framework Integration (Django MVT application)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/timonweb/django-tailwind">django-tailwind</a></b> (🥇25 ·  ⭐ 1.4K) - Django + Tailwind CSS =. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timonweb/django-tailwind) (👨‍💻 19 · 🔀 87 · 📦 4.3K · 📋 150 - 11% open · ⏱️ 22.12.2023):

	```
	git clone https://github.com/timonweb/django-tailwind
	```
- [PyPi](https://pypi.org/project/django-tailwind) (📥 84K / month):
	```
	pip install django-tailwind
	```
</details>
<details><summary><b><a href="https://github.com/oliverandrich/django-tailwind-cli">django-tailwind-cli</a></b> (🥉14 ·  ⭐ 90) - Django and Tailwind integration based on the prebuilt Tailwind CSS CLI. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oliverandrich/django-tailwind-cli) (👨‍💻 11 · 🔀 11 · ⏱️ 04.09.2024):

	```
	git clone https://github.com/oliverandrich/django-tailwind-cli
	```
- [PyPi](https://pypi.org/project/django-tailwind-cli) (📥 5.8K / month):
	```
	pip install django-tailwind-cli
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/timonweb/pytailwindcss">pytailwindcss</a></b> (🥉15 ·  ⭐ 310 · 💤) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Data exploration

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tolomea/django-data-browser">django-data-browser</a></b> (🥇18 ·  ⭐ 340) - Django app for user friendly querying of Django models. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tolomea/django-data-browser) (👨‍💻 10 · 🔀 27 · 📦 32 · 📋 37 - 13% open · ⏱️ 09.04.2024):

	```
	git clone https://github.com/tolomea/django-data-browser
	```
- [PyPi](https://pypi.org/project/django-data-browser) (📥 3.4K / month):
	```
	pip install django-data-browser
	```
</details>
<br>

## Multiple tenants

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/django-tenants/django-tenants">django-tenants</a></b> (🥇32 ·  ⭐ 1.5K) - Django tenants using PostgreSQL Schemas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-tenants/django-tenants) (👨‍💻 110 · 🔀 330 · 📦 920 · 📋 660 - 34% open · ⏱️ 27.08.2024):

	```
	git clone https://github.com/django-tenants/django-tenants
	```
- [PyPi](https://pypi.org/project/django-tenants) (📥 120K / month):
	```
	pip install django-tenants
	```
</details>
<details><summary><b><a href="https://github.com/bernardopires/django-tenant-schemas">django-tenant-schemas</a></b> (🥈27 ·  ⭐ 1.4K · 💤) - Tenant support for Django using PostgreSQL schemas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bernardopires/django-tenant-schemas) (👨‍💻 75 · 🔀 390 · 📦 430 · 📋 480 - 30% open · ⏱️ 02.07.2023):

	```
	git clone https://github.com/bernardopires/django-tenant-schemas
	```
- [PyPi](https://pypi.org/project/django-tenant-schemas) (📥 19K / month):
	```
	pip install django-tenant-schemas
	```
</details>
<details><summary><b><a href="https://github.com/citusdata/django-multitenant">django-multitenant</a></b> (🥉24 ·  ⭐ 720) - Python/Django support for distributed multi-tenant databases like Postgres+Citus. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/citusdata/django-multitenant) (👨‍💻 25 · 🔀 120 · 📦 66 · 📋 97 - 42% open · ⏱️ 30.04.2024):

	```
	git clone https://github.com/citusdata/django-multitenant
	```
- [PyPi](https://pypi.org/project/django-multitenant) (📥 25K / month):
	```
	pip install django-multitenant
	```
</details>
<details><summary><b><a href="https://github.com/raphaelm/django-scopes">django-scopes</a></b> (🥉15 ·  ⭐ 230 · 💤) - Safely separate multiple tenants in a Django database. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/raphaelm/django-scopes) (👨‍💻 6 · 🔀 15 · 📦 89 · 📋 18 - 66% open · ⏱️ 12.06.2023):

	```
	git clone https://github.com/raphaelm/django-scopes
	```
- [PyPi](https://pypi.org/project/django-scopes) (📥 5.7K / month):
	```
	pip install django-scopes
	```
</details>
<br>

## Value-as-a-Service frameworks based on Django

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_SaaS frameworks, subscription-based tutorials etc. which use Django under the hood._

<details><summary><b><a href="https://github.com/djaodjin/djaodjin-saas">djaodjin-saas</a></b> (🥇16 ·  ⭐ 560) - Django application for software-as-service and subscription businesses. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/djaodjin/djaodjin-saas) (👨‍💻 12 · 🔀 120 · 📦 9 · 📋 110 - 15% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/djaodjin/djaodjin-saas
	```
- [PyPi](https://pypi.org/project/djaodjin-saas) (📥 480 / month):
	```
	pip install djaodjin-saas
	```
</details>
<br>

## Payment and Subscription (Stripe, etc.)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/dj-stripe/dj-stripe">dj-stripe</a></b> (🥇32 ·  ⭐ 1.6K) - dj-stripe automatically syncs your Stripe Data to your local database as pre-implemented Django Models allowing you to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dj-stripe/dj-stripe) (👨‍💻 130 · 🔀 470 · 📦 1.1K · 📋 1K - 5% open · ⏱️ 23.08.2024):

	```
	git clone https://github.com/dj-stripe/dj-stripe
	```
- [PyPi](https://pypi.org/project/dj-stripe) (📥 120K / month):
	```
	pip install dj-stripe
	```
</details>
<details><summary><b><a href="https://github.com/spookylukey/django-paypal">django-paypal</a></b> (🥇26 ·  ⭐ 720) - A pluggable Django application for integrating PayPal Payments Standard or Payments Pro. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/spookylukey/django-paypal) (👨‍💻 73 · 🔀 200 · 📦 3.6K · 📋 160 - 6% open · ⏱️ 03.06.2024):

	```
	git clone https://github.com/spookylukey/django-paypal
	```
- [PyPi](https://pypi.org/project/django-paypal) (📥 19K / month):
	```
	pip install django-paypal
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/django-payments">django-payments</a></b> (🥈25 ·  ⭐ 1K) - Universal payment handling for Django. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jazzband/django-payments) (👨‍💻 65 · 🔀 270 · 📥 25 · 📦 560 · 📋 170 - 38% open · ⏱️ 29.08.2024):

	```
	git clone https://github.com/jazzband/django-payments
	```
- [PyPi](https://pypi.org/project/django-payments) (📥 9.7K / month):
	```
	pip install django-payments
	```
</details>
<details><summary><b><a href="https://github.com/pinax/pinax-stripe-light">pinax-stripe-light</a></b> (🥈21 ·  ⭐ 680 · 💤) - a payments Django app for Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pinax/pinax-stripe-light) (👨‍💻 72 · 🔀 270 · 📋 300 - 22% open · ⏱️ 28.11.2021):

	```
	git clone https://github.com/pinax/pinax-stripe-light
	```
- [PyPi](https://pypi.org/project/pinax-stripe-light) (📥 790 / month):
	```
	pip install pinax-stripe-light
	```
</details>
<details><summary><b><a href="https://github.com/django-getpaid/django-getpaid">django-getpaid</a></b> (🥈21 ·  ⭐ 440 · 💤) - Django payments processor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-getpaid/django-getpaid) (👨‍💻 30 · 🔀 110 · 📦 47 · 📋 61 - 4% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/django-getpaid/django-getpaid
	```
- [PyPi](https://pypi.org/project/django-getpaid) (📥 660 / month):
	```
	pip install django-getpaid
	```
</details>
<details><summary><b><a href="https://github.com/django-oscar/django-oscar-paypal">django-oscar-paypal</a></b> (🥈20 ·  ⭐ 160) - PayPal integration for django-oscar. Can be used without Oscar too. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/django-oscar/django-oscar-paypal) (👨‍💻 51 · 🔀 200 · 📦 160 · 📋 92 - 25% open · ⏱️ 01.09.2023):

	```
	git clone https://github.com/django-oscar/django-oscar-paypal
	```
- [PyPi](https://pypi.org/project/django-oscar-paypal) (📥 260 / month):
	```
	pip install django-oscar-paypal
	```
</details>
<details><summary><b><a href="https://github.com/silverapp/silver">silver</a></b> (🥈17 ·  ⭐ 300) - Automated billing and payments for Django with a REST API. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/silverapp/silver) (👨‍💻 24 · 🔀 75 · 📦 9 · 📋 390 - 13% open · ⏱️ 08.08.2024):

	```
	git clone https://github.com/silverapp/silver
	```
- [PyPi](https://pypi.org/project/silver) (📥 50 / month):
	```
	pip install silver
	```
</details>
<details><summary><b><a href="https://github.com/studybuffalo/django-flexible-subscriptions">django-flexible-subscriptions</a></b> (🥉15 ·  ⭐ 250 · 💤) - A subscription and recurrent billing application for Django. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/studybuffalo/django-flexible-subscriptions) (👨‍💻 14 · 🔀 54 · 📦 26 · 📋 50 - 54% open · ⏱️ 11.09.2020):

	```
	git clone https://github.com/studybuffalo/django-flexible-subscriptions
	```
- [PyPi](https://pypi.org/project/django-flexible-subscriptions) (📥 710 / month):
	```
	pip install django-flexible-subscriptions
	```
</details>
<details><summary><b><a href="https://github.com/HearthSim/dj-paypal">dj-paypal</a></b> (🥉15 ·  ⭐ 84) - Paypal integration for Django - Inspired by dj-Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HearthSim/dj-paypal) (👨‍💻 3 · 🔀 20 · 📦 26 · 📋 9 - 44% open · ⏱️ 29.02.2024):

	```
	git clone https://github.com/HearthSim/dj-paypal
	```
- [PyPi](https://pypi.org/project/dj-paypal) (📥 200 / month):
	```
	pip install dj-paypal
	```
</details>
<details><summary><b><a href="https://github.com/kogan/django-subscriptions">django-subscriptions</a></b> (🥉15 ·  ⭐ 74 · 💤) - A django package for managing subscription states. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/kogan/django-subscriptions) (👨‍💻 2 · 🔀 9 · 📦 15 · ⏱️ 29.12.2020):

	```
	git clone https://github.com/kogan/django-subscriptions
	```
- [PyPi](https://pypi.org/project/django-subscriptions) (📥 1.7K / month):
	```
	pip install django-subscriptions
	```
</details>
<details><summary><b><a href="https://github.com/oscarychen/drf-stripe-subscription">drf-stripe-subscription</a></b> (🥉14 ·  ⭐ 110) - An out-of-box Django REST framework solution for payment and subscription management using Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oscarychen/drf-stripe-subscription) (👨‍💻 5 · 🔀 17 · 📋 22 - 9% open · ⏱️ 03.06.2024):

	```
	git clone https://github.com/oscarychen/drf-stripe-subscription
	```
- [PyPi](https://pypi.org/project/drf-stripe-subscription) (📥 1.2K / month):
	```
	pip install drf-stripe-subscription
	```
</details>
<details><summary><b><a href="https://github.com/bdelate/django-flutterwave">django-flutterwave</a></b> (🥉13 ·  ⭐ 22 · 💤) - Django integration for Flutterwave Rave payments and subscriptions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bdelate/django-flutterwave) (🔀 12 · 📦 48 · ⏱️ 29.12.2020):

	```
	git clone https://github.com/bdelate/django-flutterwave
	```
- [PyPi](https://pypi.org/project/django-flutterwave):
	```
	pip install django-flutterwave
	```
</details>
<details><summary><b><a href="https://github.com/paddle-python/dj-paddle">dj-paddle</a></b> (🥉12 ·  ⭐ 80 · 💤) - Django + Paddle made Easy!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/paddle-python/dj-paddle) (👨‍💻 7 · 🔀 33 · 📋 25 - 56% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/paddle-python/dj-paddle
	```
- [PyPi](https://pypi.org/project/dj-paddle) (📥 92 / month):
	```
	pip install dj-paddle
	```
</details>
<details><summary><b><a href="https://github.com/duplxey/django-stripe-subscriptions">django-stripe-subscriptions</a></b> (🥉7 ·  ⭐ 34 · 💤) - How to handle subscription payments with Django and Stripe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/duplxey/django-stripe-subscriptions) (👨‍💻 3 · 🔀 11 · 📋 4 - 75% open · ⏱️ 20.07.2022):

	```
	git clone https://github.com/duplxey/django-stripe-subscriptions
	```
- [PyPi](https://pypi.org/project/django-stripe-subscriptions):
	```
	pip install django-stripe-subscriptions
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/agiliq/merchant">merchant</a></b> (🥈18 ·  ⭐ 1K · 💀) - A Django app to accept payments from various payment processors via Pluggable backends. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/kangasbros/django-bitcoin">django-bitcoin</a></b> (🥉15 ·  ⭐ 180 · 💀) - bitcoin payment management for django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zen4ever/django-authorizenet">django-authorizenet</a></b> (🥉12 ·  ⭐ 87 · 💀) - Django and Authorize.NET payment gateway integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zhaque/django-subscription">django-subscription</a></b> (🥉9 ·  ⭐ 180 · 💀) - Subscriptions or Recurring Billing App for django. <code>❗Unlicensed</code>
- <b><a href="https://github.com/vporton/django-payee">django-payee</a></b> (🥉4 ·  ⭐ 1 · 💤) - Accept (regular and subscription) payments in Internet (currently supports PayPal). Advanced support for subscription.. <code>❗Unlicensed</code>
</details>
<br>

## Emails

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/anymail/django-anymail">django-anymail</a></b> (🥇32 ·  ⭐ 1.7K) - Django email backends and webhooks for Amazon SES, Brevo (Sendinblue), MailerSend, Mailgun, Mailjet, Postmark, Postal,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anymail/django-anymail) (👨‍💻 65 · 🔀 130 · 📥 110 · 📦 6.6K · 📋 230 - 3% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/anymail/django-anymail
	```
- [PyPi](https://pypi.org/project/django-anymail) (📥 770K / month):
	```
	pip install django-anymail
	```
</details>
<details><summary><b><a href="https://github.com/django-ses/django-ses">django-ses</a></b> (🥈29 ·  ⭐ 1K) - A Django email backend for Amazons Simple Email Service. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/django-ses/django-ses) (👨‍💻 81 · 🔀 210 · 📦 3.1K · 📋 140 - 38% open · ⏱️ 22.08.2024):

	```
	git clone https://github.com/django-ses/django-ses
	```
- [PyPi](https://pypi.org/project/django-ses) (📥 720K / month):
	```
	pip install django-ses
	```
</details>
<details><summary><b><a href="https://github.com/ui/django-post_office">django-post-office</a></b> (🥉27 ·  ⭐ 1K) - A Django app that allows you to send email asynchronously in Django. Supports HTML email, database backed templates.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ui/django-post_office) (👨‍💻 81 · 🔀 250 · 📦 92 · 📋 250 - 37% open · ⏱️ 19.06.2024):

	```
	git clone https://github.com/ui/django-post_office
	```
- [PyPi](https://pypi.org/project/django-post-office) (📥 60K / month):
	```
	pip install django-post-office
	```
</details>
<details><summary><b><a href="https://github.com/aio-libs/aiosmtpd">aiosmtpd</a></b> (🥉24 ·  ⭐ 320) - A reimplementation of the Python stdlib smtpd.py based on asyncio. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aio-libs/aiosmtpd) (👨‍💻 43 · 🔀 93 · 📥 430 · 📋 180 - 34% open · ⏱️ 22.08.2024):

	```
	git clone https://github.com/aio-libs/aiosmtpd
	```
- [PyPi](https://pypi.org/project/aiosmtpd) (📥 480K / month):
	```
	pip install aiosmtpd
	```
</details>
<details><summary><b><a href="https://github.com/coddingtonbear/django-mailbox">django-mailbox</a></b> (🥉23 ·  ⭐ 350) - Import mail from POP3, IMAP, local email mailboxes or directly from Postfix or Exim4 into your Django application.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coddingtonbear/django-mailbox) (👨‍💻 54 · 🔀 160 · 📦 190 · 📋 160 - 12% open · ⏱️ 02.09.2024):

	```
	git clone https://github.com/coddingtonbear/django-mailbox
	```
- [PyPi](https://pypi.org/project/django-mailbox) (📥 8.7K / month):
	```
	pip install django-mailbox
	```
</details>
<br>

## Templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/adamchainz/django-htmx">django-htmx</a></b> (🥇27 ·  ⭐ 1.6K) - Extensions for using Django with htmx. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/adamchainz/django-htmx) (👨‍💻 22 · 🔀 140 · 📦 2.8K · 📋 76 - 6% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/adamchainz/django-htmx
	```
- [PyPi](https://pypi.org/project/django-htmx) (📥 240K / month):
	```
	pip install django-htmx
	```
</details>
<details><summary><b><a href="https://github.com/django-compressor/django-compressor">django-compressor</a></b> (🥈24 ·  ⭐ 2.8K) - Compresses linked and inline javascript or CSS into a single cached file. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/django-compressor/django-compressor) (👨‍💻 220 · 🔀 560 · 📋 660 - 16% open · ⏱️ 05.08.2024):

	```
	git clone https://github.com/django-compressor/django-compressor
	```
- [PyPi](https://pypi.org/project/django-compressor) (📥 620K / month):
	```
	pip install django-compressor
	```
</details>
<details><summary><b><a href="https://github.com/carltongibson/django-template-partials">django-template-partials</a></b> (🥉18 ·  ⭐ 420) - Reusable named inline partials for the Django Template Language. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carltongibson/django-template-partials) (👨‍💻 13 · 🔀 14 · 📦 160 · 📋 22 - 27% open · ⏱️ 20.08.2024):

	```
	git clone https://github.com/carltongibson/django-template-partials
	```
- [PyPi](https://pypi.org/project/django-template-partials) (📥 22K / month):
	```
	pip install django-template-partials
	```
</details>
<details><summary><b><a href="https://github.com/inertiajs/inertia-django">inertia-django</a></b> (🥉17 ·  ⭐ 280) - The Django adapter for Inertia.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inertiajs/inertia-django) (👨‍💻 8 · 🔀 31 · 📦 99 · 📋 29 - 44% open · ⏱️ 27.01.2024):

	```
	git clone https://github.com/inertiajs/inertia-django
	```
- [PyPi](https://pypi.org/project/inertia-django) (📥 4.5K / month):
	```
	pip install inertia-django
	```
</details>
<br>

## Reusable app templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/wemake-services/wemake-django-template">wemake-django-template</a></b> (🥇22 ·  ⭐ 2K) - Bleeding edge django template focused on code quality and security. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-django-template) (👨‍💻 49 · 🔀 220 · 📋 530 - 3% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/wemake-services/wemake-django-template
	```
</details>
<details><summary><b><a href="https://github.com/pydanny/cookiecutter-djangopackage">cookiecutter-djangopackage</a></b> (🥇13 ·  ⭐ 440 · 💤) - A cookiecutter template for creating reusable Django packages quickly. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/pydanny/cookiecutter-djangopackage) (👨‍💻 55 · 🔀 150 · 📋 72 - 38% open · ⏱️ 29.10.2020):

	```
	git clone https://github.com/pydanny/cookiecutter-djangopackage
	```
- [PyPi](https://pypi.org/project/cookiecutter-djangopackage):
	```
	pip install cookiecutter-djangopackage
	```
</details>
<details><summary><b><a href="https://github.com/wq/wq-django-template">wq-django-template</a></b> (🥈10 ·  ⭐ 27) - Django + NPM (Create React App) template for building REST-ful web & hybrid apps with the wq framework. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/wq/wq-django-template) (👨‍💻 4 · 🔀 7 · ⏱️ 27.03.2024):

	```
	git clone https://github.com/wq/wq-django-template
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/wildfish/cookiecutter-django-crud">cookiecutter-django-crud</a></b> (🥈9 ·  ⭐ 67 · 💀) - A cookiecutter template to create a Django app around a model with CRUD views using django-vanilla-views, a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/edx/cookiecutter-django-app">cookiecutter-django-app</a></b> (🥈9 ·  ⭐ 16 · 💤) - A cookiecutter template for creating reusable Django packages (installable apps) quickly. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mlavin/django-app-template">django-app-template</a></b> (🥉7 ·  ⭐ 54 · 💀) - A handy template for creating a new reusable Django application. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/bitlabstudio/django-reusable-app-template">django-reusable-app-template</a></b> (🥉6 ·  ⭐ 96 · 💀) - A template for kickstarting reusable Django apps, ready to be published on pypi.python.org, ready for test driven.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Opus10/python-library-template">python-library-template</a></b> (🥉6 ·  ⭐ 4) - The template for all public Django apps by Opus 10. <code>❗Unlicensed</code>
- <b><a href="https://github.com/AndreGuerra123/django-reusable-app">django-reusable-app</a></b> (🥉4 ·  ⭐ 3 · 💀) - A cookiecutter template to package Django Reusable Apps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sveetch/cookiecutter-sveetch-djangoapp">cookiecutter-sveetch-djangoapp</a></b> (🥉4 ·  ⭐ 3) - Yet another Cookiecutter template to produce a repository to start a Django application package with Python3. <code>❗Unlicensed</code>
- <b><a href="https://github.com/KryptedGaming/django-package-template">django-package-template</a></b> (🥉3 ·  ⭐ 1 · 💤) - Template for creating packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Project templates

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/apptension/saas-boilerplate">saas-boilerplate</a></b> (🥇20 ·  ⭐ 2.1K) - SaaS Boilerplate - Open Source and free SaaS stack that lets you build SaaS products faster in React, Django and AWS... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/apptension/saas-boilerplate) (👨‍💻 39 · 🔀 230 · 📋 170 - 23% open · ⏱️ 21.08.2024):

	```
	git clone https://github.com/apptension/saas-boilerplate
	```
</details>
<details><summary><b><a href="https://github.com/vintasoftware/django-react-boilerplate">django-react-boilerplate</a></b> (🥇19 ·  ⭐ 1.9K) - Django 5, React, Bootstrap 5 with Python 3 and Webpack project boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vintasoftware/django-react-boilerplate) (👨‍💻 51 · 🔀 460 · 📋 300 - 8% open · ⏱️ 02.08.2024):

	```
	git clone https://github.com/vintasoftware/django-react-boilerplate
	```
</details>
<details><summary><b><a href="https://github.com/Tobi-De/falco">falco</a></b> (🥈18 ·  ⭐ 350) - Enhance your Django developer experience: CLI and Guides for the Modern Django Developer. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Tobi-De/falco) (👨‍💻 7 · 🔀 16 · 📦 11 · 📋 63 - 14% open · ⏱️ 06.09.2024):

	```
	git clone https://github.com/Tobi-De/falco
	```
- [PyPi](https://pypi.org/project/falco) (📥 64 / month):
	```
	pip install falco
	```
</details>
<details><summary><b><a href="https://github.com/ilikerobots/cookiecutter-vue-django">cookiecutter-vue-django</a></b> (🥈14 ·  ⭐ 200) - Vue 3 + Vite + Django with no compromises. Use Vue SFCs directly in Django Templates, DRF not required. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ilikerobots/cookiecutter-vue-django) (👨‍💻 400 · 🔀 23 · 📋 15 - 26% open · ⏱️ 20.11.2023):

	```
	git clone https://github.com/ilikerobots/cookiecutter-vue-django
	```
</details>
<details><summary><b><a href="https://github.com/Lightmatter/django-hydra">django-hydra</a></b> (🥈12 ·  ⭐ 88) - A django/htmx/alpine/tailwind project template. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Lightmatter/django-hydra) (👨‍💻 38 · 🔀 10 · 📋 15 - 60% open · ⏱️ 04.09.2024):

	```
	git clone https://github.com/Lightmatter/django-hydra
	```
</details>
<details><summary><b><a href="https://github.com/thorgate/django-project-template">django-project-template</a></b> (🥈11 ·  ⭐ 120) - Thorgates Django project template - Django, React, Sass, optional Docker and more. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/thorgate/django-project-template) (👨‍💻 34 · 🔀 16 · 📋 5 - 40% open · ⏱️ 14.05.2024):

	```
	git clone https://github.com/thorgate/django-project-template
	```
</details>
<details><summary><b><a href="https://github.com/jayfk/launchr">launchr</a></b> (🥈10 ·  ⭐ 230 · 💤) - Launchr is an open source SaaS starter kit, based on Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jayfk/launchr) (🔀 40 · 📋 25 - 8% open · ⏱️ 23.01.2021):

	```
	git clone https://github.com/jayfk/launchr
	```
</details>
<details><summary><b><a href="https://github.com/stribny/sidewinder">sidewinder</a></b> (🥈10 ·  ⭐ 190) - Django starter kit that focuses on good defaults, developer experience, and deployment. Updated for Django 5. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stribny/sidewinder) (🔀 12 · 📋 27 - 14% open · ⏱️ 27.04.2024):

	```
	git clone https://github.com/stribny/sidewinder
	```
</details>
<details><summary><b><a href="https://github.com/amerkurev/django-docker-template">django-docker-template</a></b> (🥈10 ·  ⭐ 180) - Dockerized Django with Postgres, Gunicorn, and Traefik or Caddy (with auto renew Lets Encrypt). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amerkurev/django-docker-template) (👨‍💻 6 · 🔀 35 · 📋 11 - 18% open · ⏱️ 03.06.2024):

	```
	git clone https://github.com/amerkurev/django-docker-template
	```
</details>
<details><summary><b><a href="https://github.com/jefftriplett/django-startproject">django-startproject</a></b> (🥈10 ·  ⭐ 170) - Django Start Project template with batteries. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jefftriplett/django-startproject) (👨‍💻 3 · 🔀 14 · ⏱️ 26.05.2024):

	```
	git clone https://github.com/jefftriplett/django-startproject
	```
</details>
<details><summary><b><a href="https://github.com/khadegd/django-webpack-starter">django-webpack-starter</a></b> (🥉7 ·  ⭐ 59 · 💤) - Django Webpack starter template for using Webpack 5 with Django 3.1 & Bootstrap 4. Yes, it can hot-reload. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/khadegd/django-webpack-starter) (🔀 2 · 📋 3 - 33% open · ⏱️ 05.11.2020):

	```
	git clone https://github.com/khadegd/django-webpack-starter
	```
</details>
<details><summary><b><a href="https://github.com/Alex-CodeLab/django-base-template">django-base-template</a></b> (🥉6 ·  ⭐ 71 · 💤) - Project Template for Django + Bootstrap3 + pre-configured apps (like Allauth, django_compressor ). Probably the.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Alex-CodeLab/django-base-template) (👨‍💻 3 · 🔀 18 · ⏱️ 30.06.2023):

	```
	git clone https://github.com/Alex-CodeLab/django-base-template
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/jpbruinsslot/docker-django">docker-django</a></b> (🥈10 ·  ⭐ 180 · 💀) - A project to get you started with Docker and Django. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/erayerdin/sos-django-template">sos-django-template</a></b> (🥉8 ·  ⭐ 20 · 💤) - SOS Django Template is a starter template for new Django projects with modern defaults, power cable included. <code><a href="https://tldrlegal.com/search?q=WTFPL">❗️WTFPL</a></code>
- <b><a href="https://github.com/bfirsh/django-docker-heroku-template">django-docker-heroku-template</a></b> (🥉3 ·  ⭐ 36 · 💤) - Get a Django app up and running in dev, test, and production with best practices in 10 minutes. <code>❗Unlicensed</code>
- <b><a href="https://github.com/digipodium/django-bootstrap-htmx-template-2023">django-bootstrap-htmx-template-2023</a></b> (🥉1 ·  ⭐ 3) - Django Website Template 2023 is a ready-to-use template for building websites using Django, Bootstrap 5, and Htmx. <code>❗Unlicensed</code>
</details>
<br>

## Static file serving

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/evansd/whitenoise">whitenoise</a></b> (🥇33 ·  ⭐ 2.5K) - Radically simplified static file serving for Python web apps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/evansd/whitenoise) (👨‍💻 64 · 🔀 140 · 📦 450K · 📋 240 - 11% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/evansd/whitenoise
	```
- [PyPi](https://pypi.org/project/whitenoise) (📥 3.2M / month):
	```
	pip install whitenoise
	```
</details>
<br>

## Custom user

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/fusionbox/django-authtools">django-authtools</a></b> (🥇23 ·  ⭐ 370) - A custom User model for everybody!. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/fusionbox/django-authtools) (👨‍💻 31 · 🔀 94 · 📦 980 · 📋 54 - 16% open · ⏱️ 19.03.2024):

	```
	git clone https://github.com/fusionbox/django-authtools
	```
- [PyPi](https://pypi.org/project/django-authtools) (📥 14K / month):
	```
	pip install django-authtools
	```
</details>
<details><summary><b><a href="https://github.com/jcugat/django-custom-user">django-custom-user</a></b> (🥈19 ·  ⭐ 320 · 💤) - Custom user model for Django with the same behaviour as the default User class but with email instead of username. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jcugat/django-custom-user) (👨‍💻 12 · 🔀 60 · 📦 270 · 📋 24 - 4% open · ⏱️ 09.12.2022):

	```
	git clone https://github.com/jcugat/django-custom-user
	```
- [PyPi](https://pypi.org/project/django-custom-user) (📥 11K / month):
	```
	pip install django-custom-user
	```
</details>
<details><summary><b><a href="https://github.com/jambonrose/django-improved-user">django-improved-user</a></b> (🥉17 ·  ⭐ 140) - A custom Django user that authenticates via email. Follows identity and authentication best practices. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jambonrose/django-improved-user) (👨‍💻 8 · 🔀 15 · 📦 42 · ⏱️ 08.08.2024):

	```
	git clone https://github.com/jambonsw/django-improved-user
	```
- [PyPi](https://pypi.org/project/django-improved-user) (📥 450 / month):
	```
	pip install django-improved-user
	```
</details>
<details><summary><b><a href="https://github.com/jmfederico/django-use-email-as-username">django-use-email-as-username</a></b> (🥉14 ·  ⭐ 71) - A Django app to use email as username for user authentication. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jmfederico/django-use-email-as-username) (👨‍💻 2 · 🔀 10 · 📦 260 · ⏱️ 31.08.2024):

	```
	git clone https://github.com/jmfederico/django-use-email-as-username
	```
- [PyPi](https://pypi.org/project/django-use-email-as-username) (📥 4.8K / month):
	```
	pip install django-use-email-as-username
	```
</details>
<details><summary><b><a href="https://github.com/carltongibson/django-unique-user-email">django-unique-user-email</a></b> (🥉10 ·  ⭐ 96) - Enable login-by-email with the default User model for your Django project by making auth.User.email unique. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carltongibson/django-unique-user-email) (👨‍💻 3 · 🔀 5 · 📦 6 · 📋 9 - 55% open · ⏱️ 23.08.2024):

	```
	git clone https://github.com/carltongibson/django-unique-user-email
	```
- [PyPi](https://pypi.org/project/django-unique-user-email) (📥 340 / month):
	```
	pip install django-unique-user-email
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
