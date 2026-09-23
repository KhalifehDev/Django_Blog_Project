# Django Blog — Session 3 & 4

A clean Django blog project matching the practical work covered in sessions 3 and 4.

## Features
- Django project + `blog` app
- `Post` model with draft/published status
- custom manager for published posts
- Django Admin configuration
- post list page
- post detail page using slug
- shared `base.html`
- basic static CSS

## Run

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Open:
- Blog: http://127.0.0.1:8000/
- Admin: http://127.0.0.1:8000/admin/

Create a few posts in Admin. Set their status to `Published` to make them appear on the blog.
