# Free [Admin Dashboards](https://app-generator.dev/admin-dashboards/open-source/)

A curated list with **[Open-Source Admin Dashboards](https://app-generator.dev/admin-dashboards/open-source/)**, released under the MIT license and actively supported by the publishers. All mentioned templates can be used in commercial products and eLearning activities.  

> NOTE: Generate your starter on top of **Flask** and **Django** and customize: `DB Tables`, `Auth`, `Async Tasks` (Celery), `Docker`, `CI/Cd Scripts`

- 👉 [Django App Generator](https://app-generator.dev/tools/django-generator/) - free service 
- 👉 [Flask App Generator](https://app-generator.dev/tools/django-generator/) - free service

![Django App Generator - Free service provided by App-Generator](https://github.com/user-attachments/assets/d13c09d9-c8e6-4e99-bbe4-eb27bd2d7c31)
 
<br />

## [Django Datta Able](https://app-generator.dev/product/datta-able/django/)

Open-source **Django** project crafted on top of **Datta Able Dashboard**, an open-source `Bootstrap` design.
The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. 

- 👉 [Django Datta Able](https://app-generator.dev/product/datta-able/django/) - `Product Page`
- 👉 [Django Datta Able](https://django-datta.onrender.com) - `LIVE Demo`

### Features
---

- Simple, Easy-to-Extend Codebase
- Datta Able Design - Full Integration 
- [Dynamic Tables](https://app-generator.dev/docs/developer-tools/dynamic-datatables.html)
- [Dynamic API](https://app-generator.dev/docs/developer-tools/dynamic-api.html)
- CLI for Coding Tasks
- Bootstrap 5 Styling 
- Session-based Authentication, Password recovery
- DB Persistence: SQLite (default), can be used with MySql, PgSql
- Docker, CI/CD for Render
- Vite for assets management 

![Django Datta Able - Open-Source Django Starter](https://user-images.githubusercontent.com/51070104/176118649-7233ffbc-6118-4f56-8cda-baa81d256877.png)

<br />

## [Soft UI Dashboard](https://www.creative-tim.com/product/soft-ui-dashboard-tall?AFFILIATE=128200) `Laravel`

With [Laravel Soft UI Dashboard](https://www.creative-tim.com/product/soft-ui-dashboard-tall?AFFILIATE=128200) , you're getting a fast and easy way to build Laravel apps, easily style them with `Tailwind` and write `Livewire` components with a dash of `Alpine.js`.  

This free starter `takes care of` **authentication** and **user profile features** right out-of-the-box. No more writing boring code, you can now focus on the more complex aspects of your app. 

- 👉 *Frontend ONLY Version*: [Soft UI Dashboard Tailwind](https://www.creative-tim.com/product/soft-ui-dashboard-tailwind?AFFILIATE=128200) `v1.0.3`
- 🎁 More [Laravel Starters](https://www.creative-tim.com/templates/laravel-free?AFFILIATE=128200) - `all free`

[![Soft UI Dashboard TALL Free](https://user-images.githubusercontent.com/51854817/222227022-a3c6f1dd-a948-4fa3-846a-507a494cb5c2.jpg)](https://www.creative-tim.com/product/soft-ui-dashboard-tall?AFFILIATE=128200)

<br />

## [Django Rocket](https://app-generator.dev/product/rocket/django/)

Open-source **[Django Template styled with Tailwind CSS and Flowbite](https://app-generator.dev/product/rocket/django/)**.The product is designed to deliver the best possible developer experience with highly customizable feature-rich pages. 

A common set of features is provided out-of-the-box: **API, DataTables, Charts, Extended User Model, and Docker Support** under a permissive MIT License (**unrestricted usage in hobby or commercial projects**).

- 👉 [Django Rocket](https://app-generator.dev/product/rocket/django/) - `Product Page`
- 👉 [Django Rocket](https://rocket-django.onrender.com) - `LIVE Demo`

### Features
---

- Styling: **Tailwind CSS/Flowbite**
- **Extended User Model**
- [Charts](https://rocket-django.onrender.com/charts/) via ApexJS
- [DataTables](https://rocket-django.onrender.com/tables/) 
- [API](https://rocket-django.onrender.com/api/product/)
- Can be used with **SQLite**, **MySql**, **PostgreSQL**, **MsSql**
- **Docker**
- **CI/CD Integration** with Render 

![Django Rocket - Open-Source Django Starter styled with Tailwind](https://github.com/user-attachments/assets/d7527d5e-046c-4679-8f72-525290a5edd5)
  
<br />

## [Dynamic Django](https://dynamic-django.onrender.com/)

**Dynamic Programming Patterns** applied in `Python/Django` - actively supported by `AppSeed`. 

> LIVE DEMOs & [official documentation](https://app-generator.dev/docs/developer-tools/dynamic-django/index.html)

- Dynamic DataTables: https://dynamic-django.onrender.com/dynamic-dt/sales/
- Dynamic Charts: https://dynamic-django.onrender.com/dynamic-charts/sales/
  - `PIE`: [DEMO](https://dynamic-django.onrender.com/dynamic-charts/sales/?chart_id=2), [EMBED](https://dynamic-django.onrender.com/dynamic-charts/embed/2/)
  - `POLAR`: [DEMO](https://dynamic-django.onrender.com/dynamic-charts/sales/?chart_id=10), [EMBED](https://dynamic-django.onrender.com/dynamic-charts/embed/10/)
  - `DONUT`: [DEMO](https://dynamic-django.onrender.com/dynamic-charts/sales/?chart_id=8), [EMBED](https://dynamic-django.onrender.com/dynamic-charts/embed/8/)

![Dynamic Django - Dynamic Programming Patterns applied in Python/Django.](https://github.com/user-attachments/assets/2f9f6cef-23cb-4328-b12f-dcc448feaa96)

### Features 
---

- [OK] [Dynamic DataTables](https://app-generator.dev/docs/developer-tools/dynamic-datatables.html)
- [OK] Dynamic Charts
- [OK] [Dynamic API](https://app-generator.dev/docs/developer-tools/dynamic-api.html) via DRF
- [OK] Powerful `CLI` tools      

### Quick Start
---

> NOTE: Requires a [purchase](https://appseed.gumroad.com/l/devtool-dynamic-django), secured by GUMROAD.
 
```
# Clone Repo
$ git clone https://github.com/app-generator/priv-dynamic-django.git
```

> Create VENV

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

> Start the Project

```bash
$ python manage.py createsuperuser # create the admin
$ python manage.py runserver       # start the project
```

### Update model 
---

```bash
$ python
>>> from cli import *
>>> add_model('home', 'Stats')
>>> # Syntax: model_add_field('APP_NAME_HERE', 'MODEL_NAME_HERE', 'FIELD_NAME',  'FIELD_TYPE') 
>>> add_model_field('home', 'Stats', 'aInt',  'int') 
>>> add_model_field('home', 'Stats', 'aChar', 'str')
>>> add_model_field('home', 'Stats', 'aText', 'text')
```

The file is automatically reformated using `black` and DB migrated.

### DB Backup / RESET / Restore
---

```bash
$ python manage.py dbbackup  -o 20240930-001.dump  # backup 
$ python manage.py reset_db                        # RESET_DB [ Danger, all tables wipped ]
$ python manage.py dbrestore -i 20240930-001.dump  # restore 
```

--- 
Free [Admin Dashboards](https://app-generator.dev/admin-dashboards/) - Provided by **[App Generator](https://app-generator.dev/)** Service. 
